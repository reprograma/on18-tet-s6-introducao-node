1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
----------------------------------------------------------------------------------------------------------------------------------------------------------
Nível 0:
Na API com nível mais baixo de maturidade encontramos como tipo de operação, o POST e GET.Os nomes dos recursos não seguem padrão, utiliza o protocolo HTTP para comunicação, mas sem seguir qualquer tipo de regras para implementar os métodos.
----------------------------------------------------------------------------------------------------------------------------------------------------------
Nível 1:
Utiliza recursos para modelar a API, para representar cada recurso com o uso de substantivos no plural. No exemplo do crud de cliente, os recursos seriam identificados pelo substantivo “clientes”. Utilizamos os verbos HTTP de forma correta(GET,POST,DELETE,PUT).
----------------------------------------------------------------------------------------------------------------------------------------------------------
Nível 2:
Nesse nível de maturidade a mesma ideia deve ser utilizada com os verbos HTTP, eles devem ser suficientes para um CRUD (Crate, Read, Update, Delete). Para cada ação de um recurso da API são aplicados verbos diferentes.Os métodos GET, PUT e DELETE são considerados idempotente. Um método é considerado idempotente quando uma requisição idêntica pode ser executada várias vezes sem alterar o estado do servidor.
----------------------------------------------------------------------------------------------------------------------------------------------------------
Nível 3:
Último nível de maturidade de uma API é atingido quando aplicamos nela o HATEOAS (Hypermedia as the Engine of Application State). Ian Robinson define o nível da seguinte forma: “Introduz a descoberta, promovendo um caminho de deixar o protocolo com uma auto documentação.” (Fowler MARTIN, 2010, Tradução nossa). Uma API que implementa esse nível fornece aos seus clientes links que indicarão como poderá ser feita a navegação entre seus recursos. Ou seja, quem for consumir a API precisará saber apenas a rota principal e a resposta dessa requisição terá todas as demais rotas possíveis.
----------------------------------------------------------------------------------------------------------------------------------------------------------
2) qual a relação entre os metodos HTTP e o CRUD?
O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs (Verbos HTTP).
O método POST (Create) é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
O método GET (Read) solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.
O método PUT (Update) substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
O método DELETE (Delete) remove um recurso específico.
O protocolo HTTP define oito métodos de requisição (GET, POST, PUT, DELETE, HEAD, TRACE, OPTIONS e CONNECT) para indicar qual ação deve ser realizada no recurso especificado.
Os métodos GET e POST, PUT e DELETE são os mais utilizados em aplicações web. Um servidor HTTP deve implementar, pelo menos, os métodos GET e HEAD para ser funcional.
----------------------------------------------------------------------------------------------------------------------------------------------------------
3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
HATEOAS é uma restrição que faz parte da arquitetura de aplicações REST, cujo objetivo é ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API.
O acrônimo HATEOAS vem de Hypermedia As the Engine Of Application State e o termo “hypermedia” no seu nome já dá uma ideia de como este componente funciona em uma aplicação RESTful. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos.
Com isso, o cliente não precisa ter um conhecimento profundo da API, basta conhecer a URL de inicial e partir dos links fornecidos poderá acessar todos os recursos de forma circular, se guiando através das requisições realizadas.
Um exemplo clássico para explicar o HATEOAS, é o Hypertext, do HTML.
De acordo com o modelo de maturidade de Richardson, o HATEOAS é considerado o último nível de uma API RESTful. Desta forma, caso esteja procurando definir uma API que siga o padrão RESTful, o HATEOAS deve ser implementado nela.
----------------------------------------------------------------------------------------------------------------------------------------------------------
4) O que quer dizer quando dizemos que uma API é indepotente?
A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.
----------------------------------------------------------------------------------------------------------------------------------------------------------
5) Qual a diferença entre os métodos PUT e PATCH?
O método de requisição HTTP PATCH aplica modificações parciais a um recurso.
O método HTTP PUT permite apenas substituições completas de um documento. 
Em contraste ao PUT, o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos. 
Todavia, é possível realizar requisições PATCH de modo a serem idempotentes.
PATCH (assim como PUT) podem ter efeitos colaterais em outros recursos.
----------------------------------------------------------------------------------------------------------------------------------------------------------