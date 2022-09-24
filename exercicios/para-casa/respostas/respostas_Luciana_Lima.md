1)qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

        API REST Maturidade 2
        Nesse nível de maturidade a mesma ideia deve ser utilizada com os verbos HTTP, eles devem ser suficientes para um CRUD (Crate, Read, Update, Del)

2)qual a relação entre os metodos HTTP e o CRUD?


        Esses são os 4 métodos mais utilizados, e compõem o que chamamos de CRUD (Create, Read, Update and Delete), que são os métodos bases para a maioria dos softwares, são responsáveis por, em respectiva ordem: criar dados — um cadastro de usuário ou de um produto — listar esses dados, editá-los e ter a possibilidade de deleção também.

3)que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

        HATEOAS -significa Hypermedia as the Engine of Application State.(Nível 3)
        É uma restrição que faz parte da arquitetura de aplicações REST, cujo objetivo é ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API.


        Sim - De acordo com o modelo de maturidade de Richardson, o HATEOAS é considerado o último nível de uma API RESTful. 

4)O que quer dizer quando dizemos que uma API é indepotente?

        Idempotente significa que o endpoint pode ser chamado várias vezes sem resultados diferentes. Não importa se o método é chamado apenas uma ou dez vezes. O resultado deve sempre o mesmo. Isso se aplica apenas ao resultado, não ao próprio recurso.

5)Qual a diferença entre os métodos PUT e PATCH?
        O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

        O método PATCH é utilizado para aplicar modificações parciais em um recurso.

