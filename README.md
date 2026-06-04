# Sistema de Gerenciamento de Biblioteca

## Descrição

Este projeto consiste em um sistema de gerenciamento de biblioteca desenvolvido para a disciplina de Programação 4. O sistema permite o cadastro de livros, usuários e empréstimos, facilitando o controle do acervo e a administração das operações da biblioteca.

## Objetivo

Desenvolver uma aplicação web utilizando Node.js, Express.js e banco de dados relacional para gerenciar livros, usuários e empréstimos de uma biblioteca.

## Tecnologias Utilizadas

* Node.js
* Express.js
* PostgreSQL
* Git e GitHub

## Estrutura do Projeto

```text
src/
├── controllers/
├── middlewares/
├── models/
├── routes/
└── services/

sql/
└── schema.sql
```

## Funcionalidades

* Cadastro de livros
* Edição de livros
* Exclusão de livros
* Cadastro de usuários
* Registro de empréstimos
* Registro de devoluções
* Consulta de empréstimos

Instalação
Clone o repositório:
git clone https://github.com/seu-usuario/biblioteca.git
Entre na pasta do projeto:
cd biblioteca
Instale as dependências:
npm install


Configure as variáveis de ambiente utilizando o arquivo .env.example.
Execute a aplicação:
npm start

## Banco de Dados

O script de criação das tabelas está disponível em:

```text
sql/schema.sql
```

## Autor

Andrew Freitas
