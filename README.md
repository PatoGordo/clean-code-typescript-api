# clean-code-typescript-api

### Features

<ul>
  <li>
    <a href="https://typescriptlang.org/">
      <img align="center" alt="Typescript" height="20" width="30" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
      Typescript
    </a>
  </li>
  <li>
    <a href="https://expressjs.com/">
      <img align="center" alt="Express" height="20" width="30" src="https://www.vectorlogo.zone/logos/expressjs/expressjs-icon.svg">
      Express.js
    </a>
  </li>
  <li>
    <a href="https://jestjs.io/">
      <img align="center" alt="Jest" height="20" width="30" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jest/jest-plain.svg">
      Jest
    </a>
  </li>
  <li>
    <a href="https://eslint.org/">
      <img align="center" alt="ESLint" width="30" src="https://avatars.githubusercontent.com/u/6019716?s=200&v=4">
      ESLint
    </a>
  </li>
  <li>
    <a href="https://prettier.io/">
      <img align="center" alt="Prettier" width="30" src="https://raw.githubusercontent.com/prettier/prettier-logo/master/images/prettier-avatar-dark.svg">
      Prettier
    </a>
  </li>
  <li>
    <a href="https://www.vercel.com/">
      <img align="center" alt="Vercel" width="30" src="https://static-00.iconduck.com/assets.00/vercel-icon-512x449-3422jidz.png">
      Vercel
    </a>
  </li>
  <li>
    Clean Architecture
  </li>
</ul>

### How to run?

setup a .env file in the root directory and add this informations

```
ENV=DEV or PROD
DB_HOST=YOUR_POSTGRES_DB_HOST
DB_USER=YOUR_POSTGRES_DB_USER
DB_PASS=YOUR_POSTGRES_DB_PASSWORD
DB_DB=YOUR_POSTGRES_DB_DATABASE
JWT_SECRET=YOUR_JWT_SECRET
```

Install dependencies

```
yarn || npm install
```

Development server

```
yarn dev || npm run dev
```

Production server

```
yarn server || npm run server
```

### How to deploy on vercel?

Create a new vercel project add add yours environment variables

```
ENV=PROD
DB_HOST=YOUR_POSTGRES_DB_HOST
DB_USER=YOUR_POSTGRES_DB_USER
DB_PASS=YOUR_POSTGRES_DB_PASSWORD
DB_DB=YOUR_POSTGRES_DB_DATABASE
JWT_SECRET=YOUR_JWT_SECRET
```

Use the scripts below to deploy on vercel

Deploy a preview version
```
yarn vercel:preview
```

Deploy a production version

```
yarn vercel:prod
```
