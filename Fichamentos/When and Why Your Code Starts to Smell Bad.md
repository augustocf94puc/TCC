# When and Why Your Code Starts to Smell Bad

(M. Tufano _et al_., "When and Why Your Code Starts to Smell Bad," _2015 IEEE/ACM 37th IEEE International Conference on Software Engineering_, 2015, pp. 403-414, doi: 10.1109/ICSE.2015.59.)

## 1. Fichamento de Conteúdo

O artigo tem o intuiuto de estudar o quando os maus cheiros são introduzido nos códigos e o motivo deles serem introduzidos. 

Através de um estudo em mais de 5 milhões commits e uma analise manual de mais de 9 mil deles, ficou claro que o codigos são afetados por maus cheiros desde a sua criação, contradizendo o senso comum de que os maus cheiros são introduzidos somente devidos a um efeito negatrivo da evolução do software.

Outra analise que ficou clara, foi que os "recém-chegados" não são necessariamente responsáveis ​​pela introdução de bad smalls e sim os desenvolvedores com altas cargas de trabalho e pressão.

Esse maus cheiros podem  permanecer em um sistema de software por longos períodos de tempo, e causar diversos efeitos colaterais para o software, como aumento na propensão a mudanças e falhas, ou diminuição da compreensibilidade do software e manutenibilidade, por isso o autor recomenda a utilizição de ferramenteas para detectar cheiros.
 

## 2. Fichamento Bibliográfico 

* _Technical debt_ (dívida técnica) é uma metáfora introduzida por Cunningham para indicar “ _código não muito correto que adiamos para torná-lo correto_ ”

* _Bad code smells_ (Mau cheiro de código) são sintomas de más escolhas de design e implementação, representam um fator importante que contribui para o déficit técnico e possivelmente afetando a manutenibilidade de um sistema de software.

* _Classe Blob_ é  uma classe grande com diferentes responsabilidades que monopoliza a maior parte do processamento do sistema.

* _Spaghetti Code_ é uma classe sem estrutura que declara métodos longos sem parâmetros.

## 3. Fichamento de Citações 

* _"Most of times code artifacts are affected by bad smells since their creation. This result contradicts the common wisdom that bad smells are generally due to a negative effect of software evolution."_
* _"Code artifacts becoming smelly as consequence of maintenance and evolution activities are characterized by peculiar metrics' trends, different from those of clean artifacts."_
* _"Newcomers are not necessary responsible for introducing bad smalls, while developers with high workloads and release pressure are more prone to introducing smell instances."_
* _"In other words, instead of running smell detector time-to-time on the entire system, these tools could be used during commit activities (in particular circumstances, such as before issuing a release) to avoid or at least limit the introduction of bad code smells."_
