# Worst Smells and Their Worst Reason
(D. Falessi and R. Kazman, "Worst Smells and Their Worst Reasons," _2021 IEEE/ACM International Conference on Technical Debt (TechDebt)_, 2021, pp. 45-54, doi: 10.1109/TechDebt52882.2021.00014.) 

## 1. Fichamento de Conteúdo

O artigo mostra os vários tipos de “bad smells” e o motivo da sua má implementação no código. Fato é que existem demasiados espécies de “bad smells” conhecidos, como aqueles nomeados de classes God, clones de códigos e diversos outros, sendo que alguns deles, ajudam a minimizar o aperfeiçoamento dos códigos. Entretanto, nem todo “bad smells” é ruim para o programa, mas o árduo é identificar qual traz benefícios para os desenvolvedores e quais não trazem. Ao longo do artigo são apresentados os “bad smells” que não deveriam sequer existir, analisado a capacidade de mudanças associada a esses “bad smells” e, ainda, reconhecer os motivos de utilização desses “bad smells”. Para tal análise são realizadas pesquisas com 71 desenvolvedores, os quais chegam à conclusão de que dos 314 “code smells”, 80 não deveriam existir em nenhuma base de código. Ao final, o artigo chega a sete motivos para não se utilizar os “bad smells”, assim, contribuindo para que os “gates” e revisões de qualidade nunca aceitem esses “bad smells”, a fim de amentar a qualidade da base de código e, agiliza-lo e melhorar o tempo de lançamento no mercado. 

## 2. Fichamento Bibliográfico  

* _Technical debt_ (dívida técnica) é uma metáfora introduzida por Cunningham para indicar “ _código não muito correto que adiamos para torná-lo correto_ ”

* _Bad code smells_ (Mau cheiro de código) são sintomas de más escolhas de design e implementação, representam um fator importante que contribui para o déficit técnico e possivelmente afetando a manutenibilidade de um sistema de software.

* _God classes_ é  uma classe grande com diferentes responsabilidades que monopoliza a maior parte do processamento do sistema.


## 3. Fichamento de Citações 

* _“Code bad smells are symptoms of poor design and implementation thought and effort [3].”_
* _“It is well known that the majority of the development effort over software project’s lifetime [1], and up to 80% of the total cost [2] is spent in maintenance and evolution.”_
* _“External validity concerns the extent to which the research elements (subjects, artifacts, etc.) are representative of actual elements [37].”_
