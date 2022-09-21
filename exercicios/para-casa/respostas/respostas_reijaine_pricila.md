# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

API REST Maturidade 2
Na criação de uma tela de cadastro, é de extrema importância que as operações simples como, criar recurso, atualizar recurso, buscar recurso e deletar recurso sejam implementadas. Nesse nível de maturidade a mesma ideia deve ser utilizada com os verbos HTTP, eles devem ser suficientes para um CRUD (Crate, Read, Update, Delete). Para cada ação de um recurso da API são aplicados verbos diferentes.
Fonte:https://www.programmers.com.br/blog/niveis-de-maturidade-de-uma-api-rest/#:~:text=API%20REST%20Maturidade%202&text=Nesse%20n%C3%ADvel%20de%20maturidade%20a,Read%2C%20Update%2C%20Delete).

2) qual a relação entre os metodos HTTP e o CRUD?

Nesse nível de maturidade a mesma ideia deve ser utilizada com os verbos HTTP, eles devem ser suficientes para um CRUD (Crate, Read, Update, Delete).
Fonte:https://www.programmers.com.br/blog/niveis-de-maturidade-de-uma-api-rest/#:~:text=API%20REST%20Maturidade%202&text=Nesse%20n%C3%ADvel%20de%20maturidade%20a,Read%2C%20Update%2C%20Delete).

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

De acordo com o modelo de maturidade de Richardson, o HATEOAS é considerado o último nível de uma API RESTful. Desta forma, caso esteja procurando definir uma API que siga o padrão RESTful, o HATEOAS deve ser implementado nela.
Mas mesmo que não esteja seguindo o padrão RESTful a risca, é fato que o componente HATEOAS facilita e muito a manutenção de uma API e a sua integração com outras aplicações. Então, sempre que possível procure implementá-la nas APIs que desenvolver.
Fonte : https://www.treinaweb.com.br/blog/o-que-e-hateoas#:~:text=De%20acordo%20com%20o%20modelo,HATEOAS%20deve%20ser%20implementado%20nela.

4) O que quer dizer quando dizemos que uma API é indepotente?

A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.
Fonte: https://docs.aws.amazon.com/pt_br/AWSEC2/latest/WindowsGuide/ebs-direct-api-idempotency.html

5) Qual a diferença entre os métodos PUT e PATCH?

O método de requisição HTTP PATCH aplica modificações parciais a um recurso. O método HTTP PUT permite apenas substituições completas de um documento. Em contraste ao PUT , o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos.
Fonte: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PATCH

