1. qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
    
    O CRUD corresponde ao nível de maturidade 2. Antes disso o único verbo utilizado é o POST.
    
2. qual a relação entre os metodos HTTP e o CRUD?
    
    CRUD é uma sigla formada pelos métodos http mais utilizados: Create, Read, Update e Delete. 
    
3. o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
    
    “HATEOAS (Hypermedia As The Engine Of Application State ) basicamente são links e aplicação de semântica usando media-types”. Isso quer dizer que Os recursos passam a possuir links para recursos relacionados, além de links para realizar ações em cima dessas coleções, a partir desse ponto, a API se auto-documenta e possibilita a funcionalidade de descoberta.
    
    Ele é obrigatório para que uma API seja RESTful por que é o requisito para o nível de maturidade 3, o último no modelo de maturidade Richardson
    
4. O que quer dizer quando dizemos que uma API é indempotente?
    
    “Um método é considerado idempotente se o resultado de uma requisição realizada com sucesso é independente do número de vezes que é executada.”
    
    “Significa que o endpoint pode ser chamado várias vezes sem resultados diferentes. Não importa se o método é chamado apenas uma ou dez vezes. O resultado deve sempre o mesmo. Isso se aplica apenas ao resultado, não ao próprio recurso.”
    
5. Qual a diferença entre os métodos PUT e PATCH?
    
    Quando o PUT é utilizado para atualização de um recurso, todos os atributos devem ser enviados na requisição, mesmo os que não serão alterados. Já o PATCH requer que apenas os atributos que serão alterados.