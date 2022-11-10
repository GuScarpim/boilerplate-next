

## <a href="https://boilerplate-ts-guscarpim.netlify.app/" target="_blank">Deploy</a>

Isto é um [Next.js](https://nextjs.org/) boilerplate com Typescript e Styled-Components.
<br>
This is a Next.js boilerplate with Typescript and Styled-Components.

## O que é usado? <br> What is inside?

Este projeto usa as seguintes ferramentas:

- [TypeScript](https://www.typescriptlang.org/)
- [NextJS](https://nextjs.org/)
- [Styled Components](https://styled-components.com/)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Husky](https://github.com/typicode/husky)
- [GiHub Actions](https://github.com/features/actions)
- [Docker](https://www.docker.com/)
- [Snyk](https://github.com/snyk/snyk)

## Começando <br> Getting Started

Primeiro, instale as dependências do snyk e do projeto:
<br>
First, install snyk and project dependencies:

```bash
yarn global add snyk
```

```bash
yarn
```

Agora, execute o seguinte comando para inicializar o servidor:
<br>
Now, run the development server:

```bash
yarn dev
```

Abra [http://localhost:3000](http://localhost:3000) com seu navegador para ver o resultado.
<br>
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Você pode começar o seu projeto através do arquivo `pages/index.js`. A página é atualizada automaticamente conforme você edita o arquivo (Uauu).
<br>
You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.
<br />

#### Ou inicie o projeto com a imagem do docker <br> Or start project with docker image

```bash
docker-compose up
```

## Comandos <br> Commands

(Não vou traduzir isso aqui não, tá facil de entender)

- `dev`: runs your application on `localhost:3000`
- `build`: creates the production build version
- `start`: starts a simple server with the build production code
- `lint`: runs the linter in all components and pages
- `test`: runs jest in watch mode
- `test:ci`: runs jest to test all components and pages one time
- `security`: runs snyk for search vulnerabilities
- `security-fix`: fix vulnerabilities
- `protect`: update libs with vulnerabilities

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
