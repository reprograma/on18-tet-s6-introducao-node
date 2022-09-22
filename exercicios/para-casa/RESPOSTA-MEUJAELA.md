1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

R-Maturidade 2

2) qual a relação entre os metodos HTTP e o CRUD?

R-Os verbos HTTP parecem estar diretamente ligado com o CRUD

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

R- (Hypermedia As The Engine Of Application State ) basicamente são links e aplicação de semântica usando media-types. 
Não, é opicional, mas é fato que este modelo facilita e muito na manutenção do código e na integração da sua API com outras aplicações

4) O que quer dizer quando dizemos que uma API é indepotente?

R-A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.

5) Qual a diferença entre os métodos PUT e PATCH?

R- O verbo PUT é usado sempre enviando todos os atributos no payload (mesmo desejando so alterar uma informação você precisa enviar todas). O PATCH você envia somente a informação que quer alterar. 

6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)

7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"

8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades
