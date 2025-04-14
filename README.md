# Sistema em Next.js - Projeto Udemy

Este é um sistema desenvolvido durante as aulas do curso de Next.js na Udemy, com o objetivo principal de aprender e praticar os conceitos do framework.

## 🧠 Objetivo

O intuito deste projeto é colocar em prática os conhecimentos adquiridos ao longo das aulas, incluindo:

- Rotas e navegação com Next.js
- Criação de componentes reutilizáveis
- Gerenciamento de estado
- Integração com APIs
- Estilização com Tailwind CSS (ou outro framework utilizado)
- Deploy de aplicações Next.js

## 🚀 Tecnologias utilizadas

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)

## 💻 Como rodar o projeto

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/dalygames.git
```

Instale as dependências:

```bash
npm install
# ou
yarn install
```

Renomeie o .env-exemple para .env-local:
```bash
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=your_mongodb_key

NODE_ENV=development

NEXTAUTH_URL=http://localhost:3000

HOST_URL=http://localhost:3000

NEXTAUTH_SECRET=your_nextauth_key

GOOGLE_CLIENT_ID=your_google_client_id

GOOGLE_CLIENT_SECRET=GOCSPX-your_google_client_secret


```

Inicie o servidor de desenvolvimento:

```bash
npm run dev
# ou
yarn dev
```

Acesse em `http://localhost:3000`.

## 📚 Créditos

Este projeto foi desenvolvido como parte do curso de Next.js na Udemy. Todos os direitos do conteúdo pertencem ao autor do curso.

---

Sinta-se à vontade para explorar, modificar e melhorar o projeto!
