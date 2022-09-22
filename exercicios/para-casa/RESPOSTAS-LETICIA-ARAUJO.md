1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)? nivel de maturidade II
R=

2) qual a relação entre os metodos HTTP e o CRUD?
R= Os verbos HTTP está diretamente ligados ao verbos CRUD:
Creat/POST, Read/GET, Update/PUT/PATCH, Delete/DELETE

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
R= Hypermedia as the Engine of Application State - HATEOAS, é uma restrição que faz parte da estrutura de aplicações REST. Ela retorna não só os dados requiridos, como também as ações referidas a esses dados e o que pode ser feito em seguida com esses eles. Ou seja, torna a navegação pelos recursos mais fáceis de serem entendidas.
Sim. Para que uma API seja considerada RESTfull, ela deve está inserida no nível 3 do RMM.

4) O que quer dizer quando dizemos que uma API é indepotente?
R=. Quando uma API é concluída com exito, independentemente do número de vezes que as requisições sejam repetidas, elas não modificam o resultado da solicitação original ja concluída. 

5) Qual a diferença entre os métodos PUT e PATCH?
R= Ambos são utilizados para solicitar uma modificação de dados no servidor. O PUT permite apenas que façamos uma modificação/atualização completa de um recurso no servidor, ou seja, ele atualiza tudo de uma vez. Ja o PATCH faz exatamente o contrario, ele permite que façamos modificações parciais de um recurso, ou seja, por partes.