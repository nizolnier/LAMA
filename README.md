# Labenu Music Awards 🏆

<a id="en-readme"></a>
### English | [Português](#pt-readme)
Back-end project developed in Labenu's bootcamp \
LAMA is a REST API to manage the Labenu Music Awards, a festival with several bands for my class graduation! 📻

<a name="pt-menu"></a>
- [Documentation](#documentacao)
- [Getting Started](#steps)
- [Available Scripts](#en-scripts)
- [Features](#features)
- [Libraries and Frameworks](#libs)


<a id="documentation"></a>
## ✦ Documentation
- [Postman](https://documenter.getpostman.com/view/13242152/TzCJgVJY)
- [Endpoints](ENDPOINTS.md)

<a id="steps"></a>
## ✦ Getting Started
1- clone this repository

2- run this command
```
npm install
```
3- create .env file on the root directory of the project with this data:
```
// your database

DB_HOST =
DB_USER =
DB_PASSWORD = 
DB_DATABASE_NAME = 

//your key and time expire preferences

JWT_KEY =
JWT_EXPIRES_IN = 

//your cost preference

BCRYPT_COST = 
```
4- run this command

```
npm run setup
```
5- now this one
```
npm start
```
6- YOU'RE ICE CREAM IS READY!!!

<a id="en-scripts"></a>
## ✦ Available Scripts
* `npm run setup` to create tables
* `npm run start` to run the application
* `npm run dev` to run the application with hot reload
* `npm run test` to test the application

<a id="features"></a>
## ✦ Features
* Sign up
* Login
* Register a band
* Create a show
* Search for a band by its id or name
* Ver os shows de determinado dia

<a id="libs"></a>
## ✦ Libraries and Frameworks:
* cors
* express
* knex
* mysql
* dotenv
* uuid
* jsonwebtoken
* bcryptjs
* jest

*Developed with 💜 by Nicole Zolnier*

-------
<a id="pt-readme"></a>
### [English](#en-readme) | Português
Projeto back-end desenvolvido no bootcamp da Labenu. \
LAMA é uma API REST para gerenciar o Labenu Music Awards, um festival com várias bandas para a formatura da minha turma! 📻

<a name="pt-menu"></a>
- [Documentação](#documentacao)
- [Primeiros Passos](#passos)
- [Scripts Disponíveis](#pt-scripts)
- [Funcionalidades](#funcionalidades)
- [Bibliotecas e Frameworks](#bibliotecas)


<a id="documentacao"></a>
## ✦ Documentação
- [Postman](https://documenter.getpostman.com/view/13242152/TzCJgVJY)
- [Endpoints](ENDPOINTS.md)

<a id="passos"></a>
## ✦ Primeiros Passos
1- clone ese repositório

2- rode o comando abaixo
```
npm install
```
3- crie um arquivo .env na raíz do projeto com esses dados:
```
//dados do seu banco

DB_HOST =
DB_USER =
DB_PASSWORD = 
DB_DATABASE_NAME = 

//suas preferências para key e expire

JWT_KEY =
JWT_EXPIRES_IN = 

//suas preferências de cost

BCRYPT_COST = 
```
4- rode esse comando:

```
npm run setup
```
5- agora esse
```
npm start
```
6- TÁ PRONTO O SORVETINHOOOOO!

<a id="pt-scripts"></a>
## ✦ Scripts Disponíveis:
* `npm run setup` para criar as tabelas
* `npm run start` para rodar a aplicação
* `npm run dev` para iniciar a aplicação com hot reload
* `npm run test` para testar a aplicação

<a id="funcionalidades"></a>
## ✦ Funcionalidades:
* Cadastro
* Login
* Registrar uma banda
* Criar um show
* Procurar por uma banda com base no id ou nome
* Ver os shows de determinado dia

<a id="bibliotecas"></a>
## ✦ Bibliotecas e Frameworks:
* cors
* express
* knex
* mysql
* dotenv
* uuid
* jsonwebtoken
* bcryptjs
* jest

*Desenvolvido com 💜 por Nicole Zolnier*

