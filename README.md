<h1 align="center">
  <img alt="Gympoint" title="Gympoint" src="logo.png" width="200px" />
  <br>
</h1>

<p align="center">
<img alt="Github last commit" src="https://img.shields.io/github/last-commit/gusflopes/gympoint-backend">
<a href="https://www.codefactor.io/repository/github/gusflopes/gympoint-backend"><img src="https://www.codefactor.io/repository/github/gusflopes/gympoint-backend/badge" alt="CodeFactor" /></a>
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/gusflopes/gympoint-backend">
<img alt="Repository size" src="https://img.shields.io/github/repo-size/gusflopes/gympoint-backend.svg">
<a href="https://github.com/gusflopes/gympoint-backend/issues"><img alt="Repository issues" src="https://img.shields.io/github/issues/gusflopes/gympoint-backend.svg"></a>
<img alt="GitHub" src="https://img.shields.io/github/license/gusflopes/gympoint-backend.svg">
</p>

<h4 align="center">API Rest developed with Node.js, using Postgresql and Redis.</h4>
<p align="center"><strong>Current Status:</strong> Ready for Delivery</p>


<p align="center">
  <a href="#rocket-gympoint_projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#construction-configuração-inicial">Configuração Inicial</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-informacoes-importantes">Informações</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :rocket: Gympoint: Projeto GoStack 9

Projeto desenvolvido utilizando as tecnologias [Node.js][nodejs], React.js e React Native.

É composto por um **backend** em Node.js, um **frontend** web em React.js para usuário administrador, e a versão **mobile** em React Native a ser utilizada pelos alunos da Academia.

---

## :construction: Configuração Inicial
Este repositório utiliza *submodules* e foi criado para a entrega do desafio final do bootcamp GoStack 9. Para instalar basta utilizar a opção *-recurse-submodules*, usando o seguinte comando:

```bash
git clone --recurse-submodules https://github.com/gusflopes/gympoint-backend.git
```

Após clonar o repositório, basta acessar a respectiva pasta conforme a funcionalidade a ser instalada/executada.

---

## :information_source: Informações Importantes

Para clonar e rodar essa aplicação você vai precisar de [Git](https://git-scm.com), [Docker](https://www.docker.com) e [Docker Compose][https://docs.docker.com/compose/].

**We recommend you run this project using Docker and Docker-compose, so it'll build all the resources needed to run the project.**

**Running with Docker:**
```bash
docker-compose up -d
yarn
cp .env.example .env
docker-compose up -d
docker exec -it gympoint sh -c "yarn sequelize db:seed:all"
```

---

## :memo: License
This project is under the MIT license. See the [LICENSE](./LICENSE) for more information.

---

Desenvolvido por **Gustavo Lopes**. :coffe: [Entrar em contato!](https://www.linkedin.com/in/gusflopes/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[express]: https://expressjs.com
[sequelize]: https://sequelize.org
[pg]:https://github.com/brianc/node-postgres
[pg-hstore]: https://github.com/scarney81/pg-hstore
[jwt]: https://jwt.io/
[nodemailer]: https://nodemailer.com/about/
[bee]: https://bee-queue.com/
[dotenv]: https://github.com/motdotla/dotenv#readme
[bcryptjs]: https://github.com/dcodeIO/bcrypt.js/
[date-fns]: (https://date-fns.org/)
[exphbs]: https://github.com/ericf/express-handlebars
