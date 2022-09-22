1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

Nível de maturidade 2.


2- Qual a relação entre os métodos HTTP e o CRUD?
CRUD são as quatro funções básicas de um sistema para manipular um banco de dados. O HTTP é um protocolo que faz a comunicação entre cliente-servidor e possui um conjunto de métodos de requisição que irão indicar a ação a ser executada para determinado recurso.

A relação entre eles tem a ver com os 4 verbos de operação comum a ambos: create, read, update e delete, porém o CRUD é mais básico e primitivo, enquanto o HTTP possui métodos mais bem estabelecidos e complexos.


3- o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

HATEOAS é uma restrição que faz parte da arquitetura de aplicações REST, que tem como objetivo ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos. Com isso, apenas conhecendo a URL inicial e com os links fornecidos,o cliente poderá acessar todos os recursos de forma circular, guiando-se através das requisições efetuadas.

Se a API da aplicação satisfaz os 3 níveis do protocolo de HTTP, ela poderá ser considerada uma API RESTfull. O uso de HATEOS faz parte do nível 3, apresentando o seu estado atual e também o relacionamento com os demais recursos presentes na API.

4- Idempotência é a propriedade que permite que uma requisição idêntica possa ser feita uma ou mais vezes em sequência com o mesmo efeito, sem afetar o servidor. Não há efeitos colaterais. Exemplos de métodos idempotentes são: GET, HEAD, PUT e DELETE.

Logo, seguindo esta lógica, uma API é idempotente quando pode ser feita nela requisições idênticas diversas vezes, sem que ela sofra alteração no servidor

5- Comente, com exemplos, a diferença entre o PUT e o PATCH.
Ambos são usados para a requisição de alteração de dados.

PUT: altera/substitui todos os dados do recurso de destino pelos dados passados na requisição.
PATCH: atualiza parcialmente um recurso, sendo possível modificar apenas uma parte dos dados.
Exemplo PUT: