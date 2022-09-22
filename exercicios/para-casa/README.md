# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
2) qual a relação entre os metodos HTTP e o CRUD?
3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
4) O que quer dizer quando dizemos que uma API é indepotente?
5) Qual a diferença entre os métodos PUT e PATCH?
6) Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas)
7) Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1"
8) Do arquivo estados-cidade dado uma sigla retorne no terminal o lista de cidades

Respostas Para Casa Teórico:

1) * Nível de maturidade 2.

2)* A comunicação é um conceito muito importante no que tange a internet. Para que essa comunicação tenha sucesso, é necessário que alguns fatores sejam alinhados. 

* O protocolo de comunicação HTTP faz com que todos os elementos da comunicação estejam de acordo e permitindo, assim, que as aplicações web se comuniquem, realizando a conexão entre o cliente e o servidor. É um protocolo baseado em pedidos (*requests) e respostas (response) e, para realizar a comunicação define um conjunto de métodos que são responsáveis pela indicação da ação que deve ser executada. Alguns exemplos de métodos: GET, POST, PUT, PATCH, DELETE.

* Já o CRUD (Create, Read, Update, Delete) é um acrônimo para as maneiras de se operar primitivamente, principalmente em bancos de dados e armazenamentos de dados estáticos. Ocorrendo uma manipulação direta de registros ou objetos de dados.

* O protocolo HTTP e seus métodos baseia o estilo arquitetural REST e é comum que alguns desenvolvedores implementem esses verbos mapeando-os em termos CRUD:
- o verbo GET normalmente é mapeado para o CRUD Read (Leitura);
- o verbo DELETE normalmente é mapeado para o CRUD Delete (Excluir);
- o verbo PUT normalmente é mapeado para CRUD Update (Atualizar);
- o verbo POST é normalmente mapeado para o CRUD Create (Criar).

3)* HATEOAS é uma restrição que faz parte da arquitetura de aplicações REST, que tem como objetivo ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos. Com isso, apenas conhecendo a URL inicial e com os links fornecidos,o cliente poderá acessar todos os recursos de forma circular, guiando-se através das requisições efetuadas.

* Se a API da aplicação satisfaz os 3 níveis do protocolo de HTTP, ela poderá ser considerada uma API RESTfull. O uso de HATEOS faz parte do nível 3, apresentando o seu estado atual e também o relacionamento com os demais recursos presentes na API.

4)* Quer dizer que o resultado de uma requisição realizada com sucesso independe do número de vezes que foi executada. Não importando se o método foi chamado apenas uma vez ou dez vezes. O resultado deverá ser sempre o mesmo.

5)* De modo geral, os métodos PUT e PATCH são utilizados para indicar uma requisição de alteração de dados. Todavia, o verbo PATCH modifica de forma parcial os dados de um determinado recurso (como a alteração do nome de um usuário), enquanto o verbo PUT realiza, somente, a substituição total de um documento (como a alteração de todos os dados de um usuário).
Caso o recurso que pretende ser alterado pelo PUT for inexistente, um novo recurso será criado. No caso do PATCH, isso não ocorre.

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

