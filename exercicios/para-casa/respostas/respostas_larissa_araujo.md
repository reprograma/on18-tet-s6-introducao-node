Pesquise sobre os niveis de maturidade de Richardsson e responda:

1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
O nível de maturidade que corresponde ao CRUD é o dois, nesse nível a API além de usar o protocolo http para comunicação, também utiliza a semântica correta de seus verbos
Referências:
https://www.youtube.com/watch?v=P92SBaN42mQ
https://rivaildojunior.medium.com/modelo-de-maturidade-de-richardson-para-apis-rest-8845f93b288

2) qual a relação entre os metodos HTTP e o CRUD?
Para criarmos um CRUD (Create, Read, Update and Delete) é necessário utilizarmos alguns verbos ou métodos HTTP. O protocolo HTTP possui um conjunto de métodos de requisição que são responsáveis por indicar a ação que será executada. Os quatro métodos HTTP utilizados para operações básicas em um banco de dados que compõem um CRUD são:
✅ C: Create (criar) - criar um novo registro 👁 R: Read (ler) - exibir as informações de um registro ♻️ U: Update (atualizar) - atualizar os dados do registro ❌ D: Delete (apagar) - apagar um registro.
Referências:
https://github.com/reprograma/on18-tet-s6-introducao-node

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
HATEOAS são hipermídias, as rotas dentro das APIs mostrando a relação dos recursos. Ela é considerada fundamental para que uma API seja considerada RESTfull porque assim vai ter implementado o modelo de maturidade de Richardsson e vai ter implimentado os conceitos estruturais do REST.
Referências:
https://www.youtube.com/watch?v=P92SBaN42mQ
https://rivaildojunior.medium.com/modelo-de-maturidade-de-richardson-para-apis-rest-8845f93b288

4) O que quer dizer quando dizemos que uma API é indepotente?
Uma API REST pode ser considerada idempotente quando várias solicitações idênticas podem ser feitas sem que haja uma mudança no resultado e para isso métodos HTTP idempotentes são utilizados. Um método HTTP é idempotente se uma requisição idêntica pode ser feita múltiplas vezes sequencialmente com o mesmo efeito sem alterar o estado do servidor.
Referências:
https://www.youtube.com/watch?v=-50uDb_hExw

5) Qual a diferença entre os métodos PUT e PATCH?
O método PUT atualiza e substitui todos os dados do recurso de destino pelos dados da requisição e o método PATCH atualiza e modifica parcialmente um recurso.

Referências:
https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods



