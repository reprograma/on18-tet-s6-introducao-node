Conclusão do exercício para o lar.

>> 1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)? 

A partir do nível 2 

>> 2) qual a relação entre os metodos HTTP e o CRUD? 

Create -> POST. 
Read -> GET. 
Update -> PUT / PATCHS

>> 3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

HATEOAS é um modelo simples e elegante com que uma API REST pode ser desenhada para que a mesma permita que aplicações que a consumam navegue entre seus recursos através de links e URLs sem a necessidade de conhecimento denso prévio sobre a API. Não é obrigatório.


>> 4) O que quer dizer quando dizemos que uma API é indepotente?

A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.

>> 5) Qual a diferença entre os métodos PUT e PATCH? 
   
O PUT é usado para alteração de um dado completo; 
O PATCH é usado para atualização parcial (exemplo: uma propriedade).

------------------->> Questões técnicas <<------------------------

1) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)

2) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"

3) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades

>> OK