Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
    Maturidade 2

2) qual a relação entre os metodos HTTP e o CRUD?
    Os verbos do HTTP estão ligados ao CRUD, porém o CRUD é mais para requisições internas, e o HTTP é para requisições na internet.

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
    Fornece links que indicarão como poderá ser feita a navegação entre recursos, quando consumir os dados será necessário saber apenas a rota principal, a URL base da API, não é necessário se procupar com o estado do usuário pois a resposta dessa requisição terá todas as rotas possíveis.
    Não é possível que a API seja RESTfull sem HATEOS, pois se não tiver a
    HATEOS não estara seguindo todos os critérios.

4) O que quer dizer quando dizemos que uma API é idempotente?
    Uma requisição idempotente que pode ser feita várias vezes e não altera o estado do servidor. Sendo GET, HEAD, PUT e DELETE caso implementados de forma correta.
    
5) Qual a diferença entre os métodos PUT e PATCH?
    PUT: Atualiza um recurso por inteiro, mesmo que seja apenas um atributo a ser atualizado é necessário que todos os atributos sejam enviados no corpo da requisição e PATCH: atualiza um recurso parcialmente, somente o que foi solicitado atualização é enviado no corpo da requisição.