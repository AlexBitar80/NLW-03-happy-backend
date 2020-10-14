<h1 align="center">
  <img alt="Happy" title="#NextLevelWeek" src="https://raw.githubusercontent.com/AlexBitar80/NLW-03-happy-web/master/src/images/Logo.png" width="250px" />
</h1>

<h4 align="center">
	back-end da aplicação desenvolvida durante a terceira edição da Next_Level_Week(NLW) um evento gratuito promovido pela Rocketseat
</h4>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/AlexBitar80/NLW-03-happy-backend.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/AlexBitar80/NLW-03-happy-backend.svg">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/AlexBitar80/NLW-03-happy-backend.svg">
  <a href="https://github.com/AlexBitar80/NLW-03-happy-backend/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/AlexBitar80/NLW-03-happy-backend.svg">
  </a>

  <a href="https://github.com/AlexBitar80/NLW-03-happy-web/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/AlexBitar80/NLW-03-happy-backend.svg">
  </a>
</p>

<p align="center">
  <a href="#rocket-como-rodar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-tecnologias-usadas-neste-projeto">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :computer: Tecnologias usadas neste projeto

O projeto está utilizando as seguintes tecnologias:

-  [TypeScript](https://www.typescriptlang.org/)
-  [Node](https://nodejs.org/en/)
-  [Yup](https://github.com/jquense/yup)
-  [Multer](https://www.npmjs.com/package/multer)
-  [Express](https://expressjs.com/pt-br/)
-  [Typeorm](https://typeorm.io/#/)
-  [sqlite](https://www.sqlite.org/index.html)

## :rocket: Como rodar

Para clonar e rodar esse projeto você vai precisar do [Node](https://nodejs.org/en/) do [Yarn](https://yarnpkg.com/) do [Npm](https://www.npmjs.com/get-npm) e do [Git](https://git-scm.com/) instalado na rua máquina

```bash
# Faça o clone deste repositório para qualquer pasta de sua preferencia
$ git clone https://github.com/AlexBitar80/NLW-03-happy-backend

# Vá até essa pasta
$ cd (pasta que foi clonada)

# rode esses comandos para instalar as dependências
$ yarn ou npm install

# rode esse comando para inicializar as migrations
$ yarn typeorm migration:run ou npm run typeorm migration:run

# use esses comandos para rodar o API
$ yarn dev ou npm run dev

# por padrão o projeto está rodando em (http://localhost:3333)
```

## :memo: Licença

Este projeto está sob a licença MIT [LICENSE](https://github.com/AlexBitar80/NLW-03-happy-backend/blob/master/LICENSE) para mais detalhes.

