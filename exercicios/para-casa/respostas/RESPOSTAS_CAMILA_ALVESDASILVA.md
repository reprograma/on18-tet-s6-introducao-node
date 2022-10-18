# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

Baseado nos níveis de maturidade Richardsson, o CRUD corresponde ao 2º nível de maturidade. 


2) qual a relação entre os metodos HTTP e o CRUD?

Utilizando os métodos HTTP, eu posso executar o CRUD que são as operações básicas que um banco de dados faz. 

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

HATEOAS significa Hypermedia as the Engine of Application State. Uma API que utiliza HATEOAS e faz uso correto dos métodos HTTPs fornece aos seus clientes links que indicarão como poderá ser feita a nevegação entre seus recursos, então para que uma API seja considerada RESTfull é obrigatório o uso de HATEOAS. 

4) O que quer dizer quando dizemos que uma API é idempotente?

Significa dizer que uma requisição identica pode ser executada várias vezes sem alterar o estado do servidor. Mas quando utilizamos o verbo PATCH, que em sua natureza faz modificações, ele não é considerado idempotente.

5) Qual a diferença entre os métodos PUT e PATCH?

O método de requisição PATCH aplica mofificações parcias a um recurso; já o método PUT permite apenas substituições completas de um documento. 
O PATCH, diferente do PUT, não é idempotente. Isso significa dizer que requisições identicas podem obter efeitos distintos. Todavia, é possível realizar requisições PATCH de modo a serem idempotentes.

6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)
7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1" // precisa retirar as cores de dentro da array
8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades// Fazer uma função que receba uma sgla e retorne uma lista de cidades.
As respostas devem ser realizadas no seu proprio repositório, dentro da pasta para-o-lar. As respostas das questões dissertativas devem ser colocadas no arquivo **RESPOSTAS_SEU_NOME.md** 
---

Terminou o projetinho? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!