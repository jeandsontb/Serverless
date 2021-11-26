<h1 align="center">Serverless</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">

<br>

## 💻 Projeto

Esse projeto foi desenvolvido utilizando o framework serverless com a finalidade de gerar certificado para um usuário e também exibir a possibilidade de pesquisar a validade de um certificado.

## 🚀 Como executar

- Clone o repositório

### Para rodar localmente

- Rode `yarn` para instalar as dependências
- Rode o `yarn invoke` para criar o build da aplicação.
- Rode o `yarn dev` para iniciar a aplicação em ambiente local.
- Rode `yarn dynamo:install` para criar o banco em ambiente local.
- Rode `yarn dynamo:start` para iniciar o banco de dados em ambiente local.

### Para fazer o deploy

- Configurar as credenciais do usuário
- Rode `yarn deploy` para subir o projeto para AWS Lambda

## 📄 Licença

Esse projeto está sob a licença MIT.

---

Feito por Jeandson em treinamento do ignite - Rocketseat 👋🏻