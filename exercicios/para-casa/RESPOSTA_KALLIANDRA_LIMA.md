# Exercício de Casa 🏠 

## Introdução à Web e API

Pesquise sobre os niveis de maturidade de Richardsson e responda:
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?

 R - De acordo com os níveis de Richardson podemos acreditar que uma CRUD está no nível 2 de maturidadejá que o nível 3 (HATEOAS) é considerado como impraticável.
 <link src="https://www.brunobrito.net.br/richardson-maturity-model"/>


2) qual a relação entre os metodos HTTP e o CRUD?
 R - Os verbos HTTP são ferramentas necessárias para que nossa API seja RESTfull, entrentanto ser RESTful não significa ser CRUD.
 CRU - é um resource e, portanto, utiliza coisa ao invés de ação/Substantivos ao invés de verbo.
 RESTfull - pra uma API ser Restifull ela precisa obedecer a norma de construção seguindo os métodos/verbos HTTP.

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?

  R - HATOAS é considerado o nível 3 na escala de maturidade de Richardsson por conter. O objetivo dos controles hipermídia é que eles nos digam o que podemos fazer a seguir e o URI do recurso que precisamos manipular para fazê-lo.  A API começa a guiar as próximas ações através do response.

4) O que quer dizer quando dizemos que uma API é indepotente?

 R - Uma API é idepotente quando ao executar o mesmo método a resposta será sempre a mesma. São exemplos disso o PUT/DELETE e todos os
 verbos seguros (GET/HEAD/OPTIONS). O status code pode ser diferente e o servidor tem a responsabilidade de retornar dados da mesma maneira.

5) Qual a diferença entre os métodos PUT e PATCH?
 PATCH - Serve para modificação parcial de um rescurso
 PUT - Cria um novo/atualiza um recurso

A maior diferença entre eles é de que o PUT é idepotente.