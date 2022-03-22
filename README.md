# Data Lovers

## Índice

- [1. ](#1-)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Definições do Produto](#3-definições-do-produto)
- [4. Testes Unitários](#4-testes-unitários)
- [5. ](#5-)
- [7. Considerações técnicas](#7-)


## 1. Título

## 2. Resumo do projeto

O objetivo deste projeto é construir uma aplicação web que permita através de sua interface, acessar e visualizar dados sobre personagens da série Rick and Morty. O usuário poderá pesquisar por personagens mas também  ordená-los e filtrá-los a partir de categorias estabelecidas, assim como visualizar estatísticas e cálculos agregados a partir de gráficos.

Sobre a série

Rick and Morty é uma série de animação adulta norte-americana de comédia e ficção científica criada por Justin Roiland e Dan Harmon para o bloco de programação noturno Adult Swim, exibido no canal Cartoon Network.

A série estreou em 2 de dezembro de 2013 e acompanha as perigosas aventuras do cientista alcoólatra Rick e seu neto Morty, que divide seu tempo entre a vida familiar e viagens interdimensionais.

## 3. Definições do Produto

A aplicação foi pensada para atender a necessidade dos fãs da série, sejam eles fãs veteranos que desejam acessar informações adicionais sobre personagens ou novatos que querem conhecer mais sobre o universo de Rick and Morty. Para isso, foi pensado em filtros que auxiliem na busca por personagens: é possível localizar por nome,espécie,gênero, estado e ordenar os resultados em ordem alfabética.


## Histórias de usuário

Nós utilizamos as seguintes histórias de usuário para definirmos as diretrizes do nosso projeto:

<img src="img-readme/H.U 1.jpg">
<img src="img-readme/H.U 2.jpg">
<img src="img-readme/H.U 3.jpg">

Protótipo de baixa e alta fidelidade

Após a definição das histórias de usuário, discutimos como iríamos estruturar nosso site: definimos a localização dos menus, a quantidade de páginas, e de que forma apresentaríamos as informações sobre os personagens.

<img src="img-readme/prototipo_baixa_fidelidade.jpg">

Em seguida, desenhamos  uma Interface de Usuário (User Interface). Para isso, utilizamos o Figma e apresentamos o que seria o esperado para nosso projeto.

<img src="img-readme/prototipo_alta_fidelidade.jpg">

## 4. Testes Unitários

Escrevemos nosso teste para as funções de processamento, filtragem e ordenação dos dados, assim como a de cálculo de porcentagem de cada categoria de filtro. 

Nossos testes unitários possuem cobertura de 100% de statements (sentenças), functions (funções), lines (linhas), e de branches (ramos) do arquivo src/data.js, no qual contém nossas funções.

<img src="img-readme/teste_100.jpg">


## 5.  Considerações técnicas

A lógica do projeto foi implementada somente em JavaScript (ES6), HTML e CSS. 
O boilerplate contém uma estrutura de arquivos como ponto de partida, assim como toda a configuração de dependências:


src
src\data
src\Read-me IMG
src\data.js
src\estatisticas.css
src\estatisticas.html
src\estatisticas.js
src\git.png
src\index.html
src\main.js
src\package-lock.json
src\style.css
test
.babelrc
.editorconfig
.eslintignore
.eslintrc
.gitignore
package-lock.json
package.json
README.md
thumb.png

