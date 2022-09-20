Pesquise sobre os niveis de maturidade de Richardsson e responda:

1. qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

  Nivel 2, porque ele exige que se suporte os principais verbos http além do mapeamento de recursos do nivel 1.

2. qual a relação entre os metodos HTTP e o CRUD?

  CRUD, sendo as 4 funções consideradas necessárias para implementar uma aplicação de armazenamento persistente, se assemelha aos verbos HTTP em suas finalidades:

    CRUD -> HTTP
    Create -> POST
    Read -> GET
    Update -> PUT / PATCH -> PUT modificação total do recurso alvo - PATCH modificação parcial
    Delete -> DELETE

3. o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTful?

  HATEOAS (Hypermedia As The Engine Of Application State) é uma das restrições de uma API Rest e também o último nível de maturidade do modelo de Richardson, sendo assim para que uma API seja considerada completamente RESTful ela precisa seguir essa restrição que especifica que a API deve fornecer links (hypertexto) para que ela seja navegada sem necessidade de um conhecimento das URIs específicas.

4. O que quer dizer quando dizemos que uma API é idempotente?

  Uma API idempotente é uma API que o resultado de uma requisição independe do número de vezes que ela foi executada. Sendo assim é uma API menos vúlnerável a erros do usuário ou de conexão que podem repetir requisições por engano. 
  Seguindo os princípios REST nós temos uma API com os métodos GET, PUT, DELETE, HEAD, OPTIONS e TRACE idempotentes, visto que se chamados multiplas vezes com o mesmo alvo eles não alteram efetivamente o banco de dados depois de uma primeira vez bem sucedida.
  Exemplo:
  GET que só le os dados não alterando nada se chamado uma segunda vez retorna o mesmo dado.
  DELETE que se chamado duas vezes com o mesmo alvo na primeira remove o dado e na segunda retorna um erro 404. O que mantém o DELETE na classificação de IDEMPOTENTE mesmo retornando respostas diferentes pois não houve nenhuma alteração subsequente para o servidor com a requisição repetida.

  O principal método que não será automaticamente idempotente é o POST já que se chamarmos POST n vezes ele criara n objetos.

5. Qual a diferença entre os métodos PUT e PATCH?

  O PUT serve para modificar totalmente o recurso alvo, ou seja se apenas uma propriedade de um objeto foi alterado através do PUT o objeto ainda será totalmente reescrito apesar de só uma propriedade ter sofrido alteração, melhor utilizado quando o propósito é de fato alterar o objeto por completo.
  Já o PATCH serve justamente para alterações parciais e se mostra muito útil com dados mais extensos onde a alteração total levaria mais tempo.

6. Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)
7. Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"
8. Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades
