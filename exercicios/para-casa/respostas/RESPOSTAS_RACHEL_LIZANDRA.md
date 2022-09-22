## Respostas do exercício para casa 

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

* Resposta: O nível dois de maturidade faz o uso eficiente de URIs e verbos HTTP, além de utilizar também o nível 1, onde os recursos são mapeados.

2) qual a relação entre os metodos HTTP e o CRUD?

* Resposta: CRUD é o acrônimo para as 4 funções consideradas necessárias para implementar uma aplicação de armazenamento persistente, se assemelha aos verbos HTTP em suas finalidades:

    CRUD -> HTTP
    Create -> POST
    Read -> GET
    Update -> PUT / PATCH -> PUT modificação total do recurso alvo - PATCH modificação parcial
    Delete -> DELETE

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

* Resposta: HATEOAS é a sigla para Hypermedia as the Engine of Application State, promove um caminho de deixar o protocolo com uma auto documentação, facilidade de entendimento e reaproveitamento, sendo suficiente para o cliente da API ir navegando e descobrindo os recursos possíveis. HATEOAS são restrições de uma API Rest e também último nível de maturidade do modelo de Richardson, sendo assim para que uma API seja considerada completamente RESTfull ela precisa seguir essa restrição que especifica que a API deve fornecer links (hypertexto) para que ela seja navegada sem necessidade de um conhecimento das URIs específicas.


4) O que quer dizer quando dizemos que uma API é indepotente?

* Resposta: Uma API idempotente é uma API que o resultado de uma requisição independe do número de vezes que ela foi executada. Sendo assim é uma API menos vúlnerável a erros do usuário ou de conexão que podem repetir requisições por engano. 
Seguindo os princípios REST nós temos uma API com os métodos GET, PUT, DELETE, HEAD, OPTIONS e TRACE idempotentes, visto que se chamados multiplas vezes com o mesmo alvo eles não alteram efetivamente o banco de dados depois de uma primeira vez bem sucedida.
Exemplo:
GET que só lê os dados não alterando nada se chamado uma segunda vez retorna o mesmo dado.
DELETE que se chamado duas vezes com o mesmo alvo na primeira remove o dado e na segunda retorna um erro 404. O que mantém o DELETE na classificação de idempotente  mesmo retornando respostas diferentes pois não houve nenhuma alteração subsequente para o servidor com a requisição repetida. O método que não será automaticamente idempotente é o POST já que se chamarmos POST n vezes ele irá criar n objetos.

5) Qual a diferença entre os métodos PUT e PATCH?

* Resposta: O método de requisição HTTP PATCH aplica modificações parciais a um recurso. O método HTTP PUT permite apenas substituições completas de um documento. Em contraste ao PUT , o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos.

6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas) 
* Resposta: Feito.

7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"
* Resposta: Feito.

8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades
* Resposta: Feito.



