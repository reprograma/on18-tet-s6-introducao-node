# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
    Nível 0

2) qual a relação entre os metodos HTTP e o CRUD?
    Crud      HTTP
    Create    POST
    Read      GET
    Update    PUT
    Delete    DELETE

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
    HATEOAS é o nível 3 de maturidade, aonde os métodos possuem links para mais informações e documentações relevantes para fácil compreensão, é necessária para que uma API possa ser considerada RESTfull, apesar de muitas ignorarem este nível.
4) O que quer dizer quando dizemos que uma API é indepotente?
    Idempotente significa que o resultado de um método é o mesmo não importa quantas vezes você o executa.
    Exemplo: PUT altera uma string especifica para "Goiaba", não importa se o método for executado 1 vez ou 15, o resultado é o mesmo pois o método não depende de nenhum requisito anterior.
5) Qual a diferença entre os métodos PUT e PATCH?
    PUT altera uma informação, PATCH altera ou adiciona partes da informação, útil quando os dados 
    presentes estão parcialmente corretos e só é necessária uma atualização parcial
6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)
    Feito
7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"
    Feito
8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades
    Não consegui.
    
As respostas devem ser realizadas no seu proprio repositório, dentro da pasta para-o-lar. As respostas das questões dissertativas devem ser colocadas no arquivo **RESPOSTAS_SEU_NOME.md** 
---

Terminou o projetinho? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Dentro da pasta "projeto-casa" criei uma pasta "projeto-meu-nome".
- [ ] Resolvi o exercício proposto no projeto dentro da minha pasta "projeto-meu-nome".
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
- [ ] Criei um Pull Request seguindo as orientaçoes que estao nesse [documento](https://github.com/mflilian/repo-example/blob/main/exercicios/projeto-casa/instrucoes-pull-request.md).
