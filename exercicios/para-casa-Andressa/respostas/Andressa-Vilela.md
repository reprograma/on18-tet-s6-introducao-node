Pesquise sobre os niveis de maturidade de Richardsson e responda:

1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
Nível 2.

2) qual a relação entre os metodos HTTP e o CRUD?
O HTTP age como um tradutor de comando do CRUD, facilitando as ações entre API e servidor.


3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
Também conhecido como Hypermedia as the Engine of Application State, Roy Fielding descreve HATEOAS como uma das premissas necessárias para considerar um API RESTful.
Tem como elemento principal a representação hypermedia, permitindo que um documento descreva seu estado atual, e o seu relacionamento com outros elementos ou futuros estados (delete, por exemplo)


4) O que quer dizer quando dizemos que uma API é indepotente?
A idempotência garante que uma solicitação de API seja concluída apenas uma vez. Com uma solicitação idempotente, se a solicitação original for concluída com êxito, as novas tentativas subsequentes retornam o resultado da solicitação original bem-sucedida e não terão efeito adicional.


5) Qual a diferença entre os métodos PUT e PATCH?
PUT é um método de modificação de recurso onde o cliente envia dados que atualizam todo o recurso. PUT é semelhante ao POST no sentido de que pode criar recursos, mas o faz quando há uma URL definida em que PUT substitui todo o recurso, se existir, ou cria novos, se não existir.
Ao contrário da Solicitação PUT, PATCH faz atualização parcial, por exemplo, Campos que precisam ser atualizados pelo cliente, apenas esse campo é atualizado sem modificar o outro campo.