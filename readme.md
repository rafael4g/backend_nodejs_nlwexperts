# Projeto backend NLW-NODEJS

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Steps</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- NodeJS
- Typscript
- Zod
- Docker
- PostgreSQL
- Redis
- Fastify
- Prisma
- HTTP com [HOPPSCOTCH.IO](https://hoppscotch.io/)

## 💻 Projeto

Backend Websocket realtime, projeto criado em Nodejs durante o evendo NLW-NODEJS para backend utilizando banco de dados, containers e Orm para facilitar a integração de tabelas e suas dependencias, alem de muito javascript....


---

## 🎲 Steps para criação de API

Para iniciar o projeto em node.js com o arquivo packega.json
```bash
npm init -y
```

Para utilização do typescript e integração com node.js, como desenvolvimento [-D]

```bash
npm install typescript @types/node -D
```

Para criação do arquivo de configuração do typescript
```bash
npx tsc --init
```
Link para configuração do tsconfig, mantido pela microsoft, conforme a versão do node

```bash
https://github.com/microsoft/TypeScript/wiki/Node-Target-Mapping
```

Para execução de typescript, precisamos da biblioteca abaixo que convert typescript em javascript, como desenvolvimento [-D]
```bash
npm install tsx -D
```

Configurar em package.json script de desenvovimento
```bash
  "scripts": {
    "dev": "tsx watch src/http/server.ts"
  },
```

Framework Fastify
```bash
npm i fastify
```

Executar o servidor
```bash
npm run dev
```

Para Utilização do Docker, após instalado, criar o arquivo docker-compose.yml
com a imagem do Postgres, e executar o comando abaixo:
```bash
docker compose up -d
```

Para listar os containers que estão em execução
```bash
docker ps
```

Para verificar o log via ID de um container
```bash
docker logs ID
```

Para utilização de ORM [ Object Relational Mappers ], vamos utilizar Prisma
, como desenvolvimento [-D]
```bash
npm i -D prisma
```

Para iniciar o prisma
```bash
npx prisma init
```

Configurar arquivo .env com informações de user, pass e database conforme docker-compose
e na pasta `prisma` configurar o arquivo de schema

Executar o comando abaixo para criação de migrations:
```bash
npx prisma migrate dev
```

Para abrir a interface integrada do PRISMA
```bash
npx prisma studio
```

Usando client Http: HOPPSCOTCH

Instalando biblioteca de valização [ZOD]
```bash
npm install zod
```

Trabalhando com cookie
```bash
npm i @fastify/cookie
```

Biblioteca para manipulação do REDIS
```bash
npm i ioredis
```


Biblioteca para trabalhar com Websockets
```bash
npm i @fastify/websocket
```



## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](.github/LICENSE.md) para mais detalhes.

---


### Author
Feito com ♥ by Rafael d Silva