# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
API REST Maturidade 2
2) qual a relação entre os metodos HTTP e o CRUD?
Estão ligados pois os verbos http são parecidos com o método CRUD:

Create -	Criar ou adicionar novas entradas
Read -	Ler, recuperar ou ver entradas existentes
Update	- Atualizar ou editar entradas existentes
Delete (-	Remover entradas existentes

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
HATEOAS vsignigica "Hypermedia As the Engine Of Application State" e o termo “hypermedia” no seu nome já dá uma ideia de como este componente funciona em uma aplicação RESTful. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos. 
Sim, é obrigatório pois é considerado o último nível da API RESTfull.

4) O que quer dizer quando dizemos que uma API é indepotente?
Significa que uma API pode ser chamada várias vezes sem resultados diferentes. 

5) Qual a diferença entre os métodos PUT e PATCH? Ambos indicam uma requisição de alteração de dados. O PUT é usado para alteração de um dado completo dentro da HTTP
O PATCH - usado para atualização parcial.

6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas) - No arquivo filmes.js
7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1" - No arquivo colors-rgb
8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades - No arquivo estados-cidades.js

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
