# ReactJS - Star Wars

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/reactjs-starwars/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/reactjs-starwars.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/reactjs-starwars.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/reactjs-starwars.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/reactjs-starwars.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/reactjs-starwars.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/reactjs-starwars.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Esta aplicação foi criada em ReactJS realizando chamada em API e salvando os dados no Redux, e usando outras tecnologias web.

## Resumo

Esta aplicação foi desenvolvida em ReactJS com conceitos de PWA e SPA, realizando a persistência temporária das informações vindas da API do Star Wars SWAPI no Redux.
Então, se o site for atualizado todos os dados do Redux serão perdidos e o usuário terá que efetuar um novo registro no site.
O site está traduzido em dois idiomas Português e Inglês, sendo que ele verifica a região em que o usuário se encontra e o traduz automaticamente.
Obs: Se o usuário estiver numa localidade do idioma Português, é possível alterar as linhas de código no arquivo 'index.js' para testar o idioma Inglês, neste arquivo contém também a documentação para esta alteração.

## Índice

- [Capturas de Tela](#capturas-de-tela)

  - [Login](#login)

  - [Registro](#registro)

  - [Início](#início)

  - [Informação](#informacao)

  - [Sobre](#sobre)

- [Componentes](#componentes)

  - [Cabeçalho](#cabeçalho)

  - [Rodapé](#rodapé)

  - [Perfil](#perfil)

  - [Listagem](#listagem)

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

## Capturas de Tela

### Login

![Login](/.github/assets/login.png)
Esta é a primeira tela do site, para entrar o usuário terá que digitar seu usuário e senha registrados.
Se o usário não tem ainda um cadastro no site, precisa clicar em `Criar uma.` que será redirecionado a página de registro.

### Registro

![SignUp](/.github/assets/signup.png)
Esta tela é responsável pelo registro do usuário onde serão obrigatórios os preenchimentos dos campos.
Os campos são: nome, nome de usuário, e-mail, cidade, estado, senha e precisa declarar também que é fã do Star Wars.

### Início

![Home](/.github/assets/home.png)
Esta é a tela principal do site, onde você vai encontrar todas as informações sobre o Star Wars que são dividas em categorias.
Composto por: Cabeçalho, Perfil, Listagem e Rodapé

### Informação

![Info](/.github/assets/info.png)
Nesta tela encontram-se os detalhes do item selecionado pelo usuário.
Composto por: Cabeçalho, Perfil e Rodapé

### Sobre

![About](/.github/assets/about.png)
Nesta tela se encontra a versão do site e as tecnologias que foram utilizadas para construí-lo.
Composto por: Cabeçalho e Rodapé

## Componentes

### Cabeçalho

É a barra superior que você encontra atalhos para a tela principal `Início`, a tela `Sobre` e o `Sair` que redireciona para a página de Login.

### Rodapé

É a barra inferior transparente onde são encontrados os links oficiais do Star Wars.
Os atalhos são: Site Oficial, Facebook, Tumblr, Twitter, Instagram, GooglePlus, YouTube e também a autoria do site.

### Perfil

É a barra esquerda onde são encontradas as informações do usuário logado e um avatar.
As informações são todos os dados cadastrados pelo usuário.

### Listagem

É a parte central do site, onde se encontram os botões para diversas categorias.
As categorias são: pessoas, planetas, espécies, naves estelares e veículos.
Selecionando uma categoria aparecerá uma listagem específica de acordo com a mesma.
Ao clicar em um item da categoria é possível visualizar seus detalhes.

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md) e siga `Execução de Projeto para Desenvolvimento` ou `Construção e Execução de Projeto para Produção`.

## Utilizados no Projeto

### Bibliotecas

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Bootstrap](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/bootstrap.md) - Seguir CDN

- [Create React App](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md)

- [Ducks](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/ducks.md)

- [eslint-config-airbnb](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-config-airbnb.md)

- [eslint-plugin-import](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-import.md)

- [eslint-plugin-jsx-a11y](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-jsx-a11y.md)

- [eslint-plugin-react](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-react.md)

- [Formik](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/formik.md)

- [JW React Pagination Component](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/jw-react-pagination-component.md)

- [Particles.js](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/particlesjs.md)

- [React Intl](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-intl.md)

- [React Redux](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-redux.md)

- [react-router-dom](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-router-dom.md)

- [Redux](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/redux.md)

### APIs

- **[SWAPI - The Star Wars API](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api/swapi.md)**
