<h1 align="center">
    <img alt="GoBarber" src="https://res.cloudinary.com/andersonsts/image/upload/v1584495130/barber_uoxxvt.png" />
    <br />
    API - GoBarber - NodeJS
</h1>

<h4 align="center">
  :barber: Sistema para agendamento de serviços de beleza
</h4>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/andersonsts/api-gobarber-node">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/andersonsts/api-gobarber-node">

  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/andersonsts/api-gobarber-node">

  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/andersonsts/api-gobarber-node">

  <img alt="Repository issues" src="https://img.shields.io/github/issues/andersonsts/api-gobarber-node">
</p>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-executar">Executar</a>
</p>

## :rocket: Tecnologias

Este projeto utiliza as seguintes tecnologias:

-  [NodeJS](https://nodejs.org/en/)
-  [ExpressJS](https://expressjs.com/)
-  [Cors](https://github.com/expressjs/cors)
-  [Sequelize](https://sequelize.org/)
-  [JWT](https://github.com/auth0/node-jsonwebtoken)
-  [Bcryptjs](https://www.npmjs.com/package/bcryptjs)
-  [Mongoose](https://mongoosejs.com/)
-  [Multer](https://github.com/expressjs/multer)
-  [NodeMailer](https://github.com/nodemailer/nodemailer)
-  [Bee-Queue](https://github.com/bee-queue/bee-queue#processing-jobs)
-  [Sentry](https://sentry.io/welcome/)
-  [Nodemon](https://nodemon.io/)
-  [Sucrase](https://github.com/alangpierce/sucrase)
-  [Docker](https://www.docker.com/)
-  [Postgres](https://hub.docker.com/_/postgres)
-  [Postbird](https://www.electronjs.org/apps/postbird)
-  [MongoDB](https://hub.docker.com/_/mongo)
-  [Redis](https://hub.docker.com/_/redis/)
-  [Youch](https://github.com/poppinss/youch)
-  [Yup](https://github.com/jquense/yup)
-  [Dotenv](https://www.npmjs.com/package/dotenv)
-  [Date-fns](https://date-fns.org/)
-  [VS Code][vc] com [EditorConfig][vceditconfig], [ESLint][vceslint] e [Prettier](https://github.com/prettier/prettier-eslint)

## :computer: Funcionalidades
Segue abaixo algumas das funcionalidades da aplicação:
- Cadastro e login de prestadores de serviço
- Listar agendamentos marcados (por parte do prestador de serviço e do usuário)
- Cancelar agendamentos, desde que seja realizado com 2 horas de antecedência
- Upload de imagem para edição da foto de perfil do prestador de serviço
- Envio de email para o prestador de serviço quando o agendamento for realizado

## :information_source: Executar
Para clonar e executar essa aplicação você precisa do [Git](https://git-scm.com), [Node.js v10.16][nodejs] ou superior + [Yarn v1.13][yarn] ou superior instalado em sua máquina. Em seu terminal de comando, execute:

```bash
# Clone este repositório
$ git clone https://github.com/andersonsts/api-gobarber-node

# Entre no repositorio
$ cd api-gobarber-node

# Instale as dependências
$ yarn install

# Execute a aplicação
$ yarn dev
```

:exclamation: Para conhecer o frontend dessa aplicação, acesse: [GoBarber - React](https://github.com/andersonsts/gobarber-react)

---

:rocket: Feito por Anderson Santos :wave: [Entre em contato!](https://www.linkedin.com/in/andersonst-dev)


[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint


