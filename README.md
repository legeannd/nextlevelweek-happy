<p align="center">
  <img src="web/src/images/logo.svg"/>
</p>

# Happy
![stacks](https://img.shields.io/badge/NodeJS-v12.18.4-brightgreen) ![stacks](https://img.shields.io/badge/ReactJS-v16.13.1-brightgreen)  ![stacks](https://img.shields.io/badge/Stack-Typescript-blue) ![GitHub](https://img.shields.io/github/license/legeannd/nextlevelweek-happy)


<p align="center">
  <img src="uploads/Capa.png"/>
</p>

<p align="center">
  <img width="600" src="uploads/web.gif"/>
</p>


* [Content (en-US)](#section-en_us)
* [Conteúdo (pt-BR)](#secao-pt_br)

---

## About the project <a id="section-en_us"></a>

Happy is a platform idealized to bring info about orphanages nearby, so it can be easier to found them, facilitating the adoption process.
The backend was created using Node.js and it's responsible for register a new orphanage, with images and infos of the place, and also return data from orphanages already registered.
The web application was made in React, and is responsible for sending the registration data of a new orphanage, in addition to dynamically showing on a map all orphanages already registered.

## Content
  * [Techs](#techs)
  * [How to run the project](#installation)
    * [Installation - Back-end](#installation-back)
    * [Installation - Front-end](#installation-front)

## Techs <a id="techs"></a>

- [x] NodeJS
- [x] Express
- [x] Typeorm
- [x] React
- [x] Axios
- [x] Leaflet

## How to execute the project <a id="installation"></a>
To execute the project, you'll need to have Node and NPM or Yarn installed to setup all the dependencies.


### Installation - Back-end (Server and API) <a id="installation-back"></a>

```bash
cd server
npm install
npm run typeorm migration:run
npm run dev
```

If you are using Yarn, use this:
```bash
cd server
yarn install
yarn typeorm migration:run
yarn dev
```

### Installation - Front-end (Web) <a id="installation-front"></a>

```bash
cd web
npm install
npm start
```

If you are using Yarn, use this:
```bash
cd web
yarn install
yarn start
```

After finishing installation, the web page will be open in your browser.

---

## Sobre o projeto <a id="secao-pt_br"></a>

O happy é uma plataforma que tem como objetivo trazer informações sobre orfanatos da região, para que possam ser encontrados mais facilmente, facilitando assim o processo de adoção. 
O servidor backend foi feito em Node.js e é responsável por fazer o cadastro de um novo orfanato, contendo imagens do lugar e suas informações, além de retornar dados sobre os orfanatos cadastrados. 
O aplicativo web foi feito em React, e é responsável por enviar as informações de cadastro de um novo orfanato, além de mostrar dinamicamente num mapa todos os orfanatos já cadastrados.

## Conteúdos 
  * [Tecnologias](#tecnlogias)
  * [Como executar o projeto](#instalacao)
    * [Instalação - Back-end](#instalacao-back)
    * [Instalação - Front-end](#instalacao-front)

## Tecnologias <a id="tecnologias"></a>

- [x] NodeJS
- [x] Express
- [x] Typeorm
- [x] React
- [x] Axios
- [x] Leaflet

## Como executar o projeto <a id="instalacao"></a>
Para executar o projeto, você irá precisar ter o Node e o NPM ou Yarn instalados para baixar as dependências.


### Instalação - Back-end (Server e API) <a id="instalacao-back"></a>

```bash
cd server
npm install
npm run typeorm migration:run
npm run dev
```

Se estiver usando Yarn, utilize
```bash
cd server
yarn install
yarn typeorm migration:run
yarn dev
```

### Instalação - Front-end (Web) <a id="instalacao-front"></a>

```bash
cd web
npm install
npm start
```

Se estiver usando Yarn, utilize
```bash
cd web
yarn install
yarn start
```

Quando terminar, a página da aplicação web será aberta no navegador.

---
###### Developed on Next Level Week from [Rocketseat](https://rocketseat.com.br) by [Gean Lucas](https://www.linkedin.com/in/geanlucaas/) :rocket:.