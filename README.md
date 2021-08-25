<h1 align="center">Sistema de Cadastro de Usuário e TAG</h1>

## Funcionamento do sistema

- Cadastro de usuário

  [ x ] Não é permitido cadastrar mais de um usuário com o mesmo e-mail

  [ x ] Não é permitido cadastrar usuário sem e-mail

- Cadastro de TAG

  [ x ] Não é permitido cadastrar tag sem nome

  [ x ] Não é permitido cadastrar mais de uma tag com o mesmo nome

  [ x ] Não é permitido o cadastro por usuários que não sejam administradores

- Cadastro de elogios

  [ ] Não é permitido um usuário cadastrar um elogio para si

  [ ] Não é permitido cadastrar elogios para usuários inválidos

  [ ] O usuário precisa estar autenticado na aplicação

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [JSONWebToken](https://github.com/auth0/node-jsonwebtoken#readme)

## 💻 Projeto

Este projeto foi desenvolvido com base nos estudos node.js, typescript da rocketseat

## 🚀 Como executar

- Clone o repositório
- Rode `yarn` para baixar as dependências
- Rode `yarn typeorm migration:run` para criar as tabelas do banco de dados.
- Rode o `yarn dev` para iniciar a aplicação.

Por fim, a aplicação estará disponível em `http://localhost:3000`

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
Feito com 💜 &nbsp;by Rocketseat 👋🏻 &nbsp;[Participe da nossa comunidade!](https://discord.gg/gKUVrzrPrU)
