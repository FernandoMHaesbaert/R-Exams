# R-Exams
Aqui disponibilizarei alguns exemplos de questões desenvolvidas em Rmarkdown para serem usadas no Moodle.

[R/exams](https://www.r-exams.org/) é um pacote open-source que pode ser utilizado e aperfeiçoado livremente. Permite a criação de exercícios gerados dinamicamente que podem ser exportados para o ambiente Moodle. A maior vantagem da utilização deste sistema é a possibilidade de gerar diferentes versões do mesmo exercício com diferenças aleatórias entre eles.
  
No console do R, instale o pacote `R/exams` executando o código:  
`install.packages(“exams”)`


## Criação em R/exames  
Assim como para outras funções do R/exams, o ponto de partida é escrever o exercício (potencialmente) dinâmico em R. A partir desse exercício, no formato R/Markdown, uma série de replicações aleatórias podem ser extraídas usando `exams2moodle()`.  
O R/Exams suporta os tipos de exercícios : escolha única (schoice), escolha múltipla (mchoice), numérico (num), string (string) ou combinações destes (cloze). 


## Criando uma questão com Rmarkdown  
Para criar uma questão com R Markdown, clicamos no botão:  
File > New File > RMarkdown.

