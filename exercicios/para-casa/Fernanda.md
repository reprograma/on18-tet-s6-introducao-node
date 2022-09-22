Pesquise sobre os niveis de maturidade de Richardsson e responda:

1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

-create: criar um novo registro;
-read: ler/exibir as informações de um registro;
-update: atualizar os dados do registro;
-delete: apagar um registro.

2) qual a relação entre os metodos HTTP e o CRUD?

Os verbos HTTP está diretamente ligados ao verbos CRUD:
Creat/POST, Read/GET, Update/PUT/PATCH, Delete/DELETE

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

HATEOAS é um acrônimo/abreviação para "Hipermedia As The Engine Of Application State", é uma restrição que faz parte da arquitetura REST e que está vinculado às Web API´s.
Este modelo, desenvolvido por Leonard Richardsson, traz o modelo Rest para um novo nível, cujo objetivo é ajudar os clientes que consomem o serviço REST/Web API.

Imagine que você faz uma requisição a uma API, e ela vai retornar um objeto ou coleção de objetos como resposta. Essa seria a WEB API sem usar HATEOAS.

De acordo com o modelo de maturidade de Richardson, HATEOAS é considerado o ultimo nível do REST. Isto significa que em uma aplicação HATEOAS presume-se que os verbos padrão de uma aplicação REST como GET, POST, PUT e DELETE também são adotados. Sendo que cada um deles provê ao cliente os links necessários ao acesso à uma informação.

4) O que quer dizer quando dizemos que uma API é idempotente?

A idempotência garante que a solicitação de API seja concluída apenas uma vez, ou seja, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.
Quando implementados corretamente, o GET, HEAD, PUT e DELETE são métodos idempotentes.

Para ser idempotente, somente o estado atual do back-end de um servidor deve ser considerado, o código de status retornado por cada requisição pode variar: a primeira chamada de um DELETE vai provavelmente retornar um 200, enquanto as chamadas sucessivas vão provavelmente retornar 404. 
Outra implicação do DELETE ser idempotente é de que os desenvolvedores não deveriam implementar APIs RESTful com a funcionalidade de deleção de última entrada usando o método DELETE.

5) Qual a diferença entre os métodos PUT e PATCH?

Ambos são usados para indicar uma requisição de alteração de dados, porém:

-o PUT é usado para alterações completas de um documento, ex:
Exemplo: (/usuario/1234) :
Resultado: {'id': 1234, 'name': 'Joao', 'idade': 25, 'documento': '123.321.12-X'}

-o PATCH é usado para atualização parcial, quando você não quer mandar o payload completo, ex:
Exemplo: (/usuario/1234) :
Resultado: {'name': 'João'}