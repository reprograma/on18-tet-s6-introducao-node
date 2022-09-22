## 1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
-Até onde eu vi, existem três tipos de maturidade de API Rest
-A CRUD está na maturidade de nível dois.

## 2) qual a relação entre os metodos HTTP e o CRUD?
-CRUD = Create, Read, Update, Delete
-HTTP = Post, Get, Put/patch, Delete
-Pelo que eu entendi, o que for escrito em CRUD, é entendido pelo HTTP. Mas no geral são a mesma coisa.

## 3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
-Sabe quando a gente entra em um site, e dentro do site você vai se guiando para outras páginas? O HATEOAS é isso: hyperlinks!
-Se você entra no site reprograma.com, e ao acessar outra página, aparece reprograma.com/todasemtech, a parte /todasemtech faz parte do HATEOAS. Isso é muito importante.
-A gente utiliza o HATEOAS para linkar diretamente com os domínios do site, ou domain.

## 4) O que quer dizer quando dizemos que uma API é idempotente?
-Significa que em uma API idempotente vai garantir que o usuário só solicite algo uma vez. Se a solicitação original for concluída com êxito, qualquer outra tentativa vai retornar para "solicitação original bem sucedida". Isso é ótimo para impedir que por exemplo utilizem cupons só uma vez. Ou só seja feita uma compra.

## 5) Qual a diferença entre os métodos PUT e PATCH?
-Diferença um:
O método PUT é idempotente.
O método PATCH não é idempotente, ou seja, pode fazer requisições sucessivas idênticas que podem obter efeitos distintos.
-Diferença dois:
O método patch aplica modificações parciais a um recurso, já o método PUT permite apenas substituições completas de um documento. Isso implica que o PUT pode criar novos recursos, mas o patch não. O patch não cria, ele modifica parcialmente.


## 6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)
-

## 7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"
-

## 8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades
-