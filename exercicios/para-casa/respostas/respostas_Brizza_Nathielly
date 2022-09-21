Pesquise sobre os níveis de maturidade de Richardson e responda:

1) Qual nível de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

Os níveis de maturidade de Richardson vão do zero ao três. 
O nível de maturidade em que a API suporta os diversos verbos HTTP, como por exemplo:
POST - Criar; GET - Ler; PUT - Atualizar; DELETE - Excluir; PATCH - Atualizar parcialmente; é o nível dois.
O nível dois de maturidade faz o uso eficiente de URIs e verbos HTTP.
Nos níveis anteriores o protocolo HTTP estava sendo usado superficialmente.
No nível dois as API's começam a se aproximar do que o RESTFul espera.

Fonte: https://www.brunobrito.net.br/richardson-maturity-model/

2) Qual a relação entre os métodos HTTP e o CRUD?

O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs (Verbos HTTP).
O método POST (Create) é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
O método GET (Read) solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.
O método PUT (Update) substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
O método DELETE (Delete) remove um recurso específico.

Fonte: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods

O protocolo HTTP define oito métodos de requisição (GET, POST, PUT, DELETE, HEAD, TRACE, OPTIONS e CONNECT) para indicar qual ação deve ser realizada no recurso especificado.
Os métodos GET e POST, PUT e DELETE são os mais utilizados em aplicações web. Um servidor HTTP deve implementar, pelo menos, os métodos GET e HEAD para ser funcional.

Fonte: https://tecnoblog.net/responde/o-que-e-http/

3) O que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

HATEOAS é uma restrição que faz parte da arquitetura de aplicações REST, cujo objetivo é ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API.
O acrônimo HATEOAS vem de Hypermedia As the Engine Of Application State e o termo “hypermedia” no seu nome já dá uma ideia de como este componente funciona em uma aplicação RESTful. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos.
Com isso, o cliente não precisa ter um conhecimento profundo da API, basta conhecer a URL de inicial e partir dos links fornecidos poderá acessar todos os recursos de forma circular, se guiando através das requisições realizadas.
Um exemplo clássico para explicar o HATEOAS, é o Hypertext, do HTML.

De acordo com o modelo de maturidade de Richardson, o HATEOAS é considerado o último nível de uma API RESTful. Desta forma, caso esteja procurando definir uma API que siga o padrão RESTful, o HATEOAS deve ser implementado nela.

Fonte: https://www.treinaweb.com.br/blog/o-que-e-hateoas

4) O que quer dizer quando dizemos que uma API é indepotente?

A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.

Fonte: https://docs.aws.amazon.com/pt_br/AWSEC2/latest/WindowsGuide/ebs-direct-api-idempotency.html

5) Qual a diferença entre os métodos PUT e PATCH?

O método de requisição HTTP PATCH aplica modificações parciais a um recurso.
O método HTTP PUT permite apenas substituições completas de um documento. 
Em contraste ao PUT, o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos. 
Todavia, é possível realizar requisições PATCH de modo a serem idempotentes.
PATCH (assim como PUT) podem ter efeitos colaterais em outros recursos.

Fonte: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PATCH