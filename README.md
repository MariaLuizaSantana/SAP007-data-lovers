# Data Lovers

## Índice

- [1. Título e Imagem](#1-título-e-imagem)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Definições do Produto](#3-definições-do-produto)
- [4. Testes Unitários](#4-testes-unitários)
- [5. Considerações técnicas](#5-considerações-técnicas)
- [6. Pessoas que desenvolveram o Projeto](#6-pessoas-que-desenvolveram-o-projeto)


## 1. Título e Imagem

O Projeto data lovers foi criado para um bootcamp da Laboratória com o objetivo de colocar em prática todo o conteúdo do objetivo de aprendizagem. O tema escolhido foi o de Rick & Morty.


## 2. Resumo do projeto

O objetivo deste projeto é construir uma aplicação web que permita através de sua interface, acessar e visualizar dados sobre personagens da série Rick and Morty. O usuário poderá pesquisar por personagens mas também  ordená-los e filtrá-los a partir de categorias estabelecidas, assim como visualizar estatísticas e cálculos agregados a partir de gráficos.

Sobre a série

Rick and Morty é uma série de animação adulta norte-americana de comédia e ficção científica criada por Justin Roiland e Dan Harmon para o bloco de programação noturno Adult Swim, exibido no canal Cartoon Network.

A série estreou em 2 de dezembro de 2013 e acompanha as perigosas aventuras do cientista alcoólatra Rick e seu neto Morty, que divide seu tempo entre a vida familiar e viagens interdimensionais.

## 3. Definições do Produto

A aplicação foi pensada para atender a necessidade dos fãs da série, sejam eles fãs veteranos que desejam acessar informações adicionais sobre personagens ou novatos que querem conhecer mais sobre o universo de Rick and Morty. Para isso, foi pensado em filtros que auxiliem na busca por personagens: é possível localizar por nome,espécie,gênero, estado e ordenar os resultados em ordem alfabética.


## Histórias de usuário

Nós utilizamos as seguintes histórias de usuário para definirmos as diretrizes do nosso projeto:

<img alt="história de usuário nº 3" src="src\H.U 1.png">
<img alt="história de usuário nº 3" src="H.U 2.jpg">
<img alt="história de usuário nº 3" src="H.U 3.jpg">

Protótipo de baixa e alta fidelidade

Após a definição das histórias de usuário, discutimos como iríamos estruturar nosso site: definimos a localização dos menus, a quantidade de páginas, e de que forma apresentaríamos as informações sobre os personagens.

<img src="img-readme/prototipo_baixa_fidelidade.jpg">

Em seguida, desenhamos  uma Interface de Usuário (User Interface). Para isso, utilizamos o Figma e apresentamos o que seria o esperado para nosso projeto.

<img src="img-readme/prototipo_alta_fidelidade.jpg">

## 4. Testes Unitários

Escrevemos nosso teste para as funções de processamento, filtragem e ordenação dos dados, assim como a de cálculo de porcentagem de cada categoria de filtro. 

Nossos testes unitários possuem cobertura de 100% de statements (sentenças), functions (funções), lines (linhas), e de branches (ramos) do arquivo src/data.js, no qual contém nossas funções.

<img src="teste_100.jpg">


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

## 6. Pessoas que desenvolveram o Projeto

Esse projeto foi desenvolvido por

 Louiza Lima, Squad 5.

e

 Maria Luiza Costa, Squad 1.






# Data Lovers

## Índice

- [1. Projeto 2 - Data Lovers](#1-projeto-2-data-lovers)
- [2. Usuário](#2-usuário)
- [3. Histórias do usuário](#3-histórias-do-usuário)
- [4. Protótipos](#4-protótipos)
- [5. Testes unitários](#5-testes-unitários)
- [6. Tecnologias](#6-tecnologias)
- [7. Considerações técnicas](#7-considerações-técnicas)
- [8. Resultado](#8-resultado)
- [9. Desenvolvedoras](#9-desenvolvedoras)

---

## 1. Projeto 2 - Data Lovers

Neste projeto foi criada uma página web com o objetivo de disponibilizar aos fãs dados sobre o desenho "Rick and Morty".

Por meio do site, o usuário tem a experiência de navegar pelo o universo dos seus personagens favoritos e outras informações até então desconhecidas.

Para fornecer tal experiência, utilizamos o consumo e manipulação da API rickandmorty.js.

![Boas Vindas](https://media.giphy.com/media/AkHxaxefQOsCH0Qq2j/giphy.gif)
![Pagina boas vindas](https://media.giphy.com/media/Qtacv6vkkiUE4udtEG/giphy.gif)

### Acesso ao site

Clique <a href="https://lalaonde.github.io/SAP007-data-lovers/" target="_blank" title="Clique aqui!">aqui</a> ou escanei o QR Code a baixo.<br>
<img alt="QRcode" src="img-readme/qrcode.png" width="200px">

---

## 2. Usuário

Ao navegar pelas redes sociais, grupos de interação e hashtags, percebemos que, claro, exsitem muitas informações acerca do desenho, no entanto dispersas. Por isso, afim de concentrar os dados num único local, como uma biblioteca, e facilitar a vida dos fãs, idealizamos o "Portal Rick and Morty".

Para orientar a nossa ideia e construção do código, foram escritas as histórias do usuário a seguir.

Para cada história do usuário utilizamos os [5. Testes unitários](#5-testes-unitários) como definição de pronto.

### 3. Histórias do usuário

#### 3.1 O usuário quer visualizar todos os personagens.

Para isso criamos cards para cada personagem e suas respecptivas fotos.

#### 3.2. O usuário quer ver as informações de cada personagem.

Aqui acrescentamos em cima do card uma animação com as informações.

#### 3.3 O usuário quer navegar nas informações e fazer buscas específicas, por meio de filtros.

Utiizamos um formulário para identicar quais filtros seriam interessantes para os fãs. Os 4 principais foram: gênero, status, espécie e ordenação alfabética.

![Pesquisa de usuário](https://media.giphy.com/media/DikbKy2JcdkgWC1Qzr/giphy.gif)

#### 3.4 O usuário quer buscar pelo nome

Como existem 493 personagens, pode ser difícil achar sua personagem favorita. Portanto, para facilitar a usabilidade, inserimos um campo de busca.

#### 3.5 O usuário quer saber quanto esses filtros retornam em porcentagem.

Ex: uma fã do desenho se interessa por questões de gênero e quer saber quantas personagens femininas existem, qual a porcentagem delas nesse universo.

#### 3.6 O usuário quer fazer novas buscas e não quer dar refresh na tela, mas sim um botão que limpe todos os campos.

Inserimos um botão "limpar filtros".

---

## 4. Protótipos

### 4.1 Protótipo de baixa fidelidade

4.1.1 Página de boas vindas

<img alt="Protótipo baixa fidelidade" src="img-readme/prot-baixa1.png" width="350px">

4.1.2 Página principal

<img alt="Protótipo baixa fidelidade" src="img-readme/prot-baixa2.png" width="350px">

### 4.2 Protótipo de alta fidelidade

4.2.1 Página de boas vindas

<img alt="Protótipo alta fidelidade" src="img-readme/prot-alta-fide2.png" width="400px">

4.2.2 Página principal com os Cards

<img alt="Protótipo alta fidelidade" src="img-readme/prot-alta-fide1.png" width="350px">

### 4.3 Paleta de cores

Uitlizamos o site coolors.com para sua criação.

<img alt="Paleta de cores" src="img-readme/paleta.png" width="250px">

---

## 5. Testes unitários

Os testes unitários foram desenvolvidos para fazer com que o projeto rode adequadamente, nele você consegue verificar se cada função está dando o retorno esperado.

<img alt="Teste" src="img-readme/testes-data.png" width="400px">

---

## 6. Teste de usabilidade

Após a primeira pesquisa com potenciais usuários e mapeamento das suas necessidades enquanto fãs, e consequentemente a construção das histórias do usuário, criamos também um formulário para os fãs deixarem seu feedback após testarem o site.

## ![Teste usabilidade](https://media.giphy.com/media/0RqzPU7aT3kLHpR0jr/giphy.gif)

---

## 7. Tecnologias

![Getting Started](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)

![Getting Started](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)

![Getting Started](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[![git](https://badgen.net/badge/icon/git?icon=git&label)](https://git-scm.com)

[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)

## 8. Resultado

8.1 Celulares e tablets

## ![Final](https://media.giphy.com/media/Qtacv6vkkiUE4udtEG/giphy.gif)

## 9. Desenvolvedoras

<h2><a style="color:purple" href="https://github.com/lalaonde" target="_blank">Layssa Aragão</a> e <a style="color:purple" href="https://github.com/daianeoltramari">Daiane Oltramari</a></h2>

![Final](https://media.giphy.com/media/Qs0QEnugOy0xIsFkpD/giphy.gif)