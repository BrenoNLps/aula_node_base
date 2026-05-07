# Desenvolvimento Back-end

Este projeto foi desenvolvido como material prático da disciplina de **Desenvolvimento de Software** da **FATEC Porto Ferreira**, ministrada pelo **Prof. M. Sc. Felipe Ivo da Silva**.

O objetivo desta aula é introduzir o desenvolvimento back-end com Node.js e Express, demonstrando como criar um servidor, definir rotas, utilizar middlewares, configurar variáveis de ambiente, renderizar páginas pelo servidor com Template Engines e realizar o deploy da aplicação na nuvem.

## Conteúdo abordado

- Node.js e NPM
- Express — criação de servidores e rotas
- Middlewares
- Variáveis de ambiente com dotenv (.env)
- Rotas com Express
- Template Engines e SSR (Server Side Rendering)
- Deploy no Render

## Estrutura do projeto

```
api/
├── views/
│   ├── index.ejs
│   └── usuario.ejs
├── .env
├── .gitignore
├── index.js
├── package.json
├── routes.js
└── server.js
```

## Como rodar

```bash
npm install
node index.js
```

## Variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto com:

```
PORT=3000
```

## Deploy

O projeto está hospedado no **Render**.
