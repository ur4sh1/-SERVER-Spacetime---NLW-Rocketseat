#Exercício de Node
<h1 align="center">:file_cabinet: API - Spacetime</h1>

## :memo: Descrição
Projeto criado no evento da Rocketseat NLW-Spacetime

## :books: Funcionalidades
* Servidor node para comunicação ao banco de dados

## :wrench: Tecnologias utilizadas
* Node.js
* Fastify
* Zod
* Prisma
* Typescript
* Docker

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
git clone git@github.com:ur4sh1/-SERVER-Spacetime---NLW-Rocketseat.git
```
Instalar o npm
```
npm i
```
Executar
```
npm run dev
```

## :wrench: Histórico de comandos

Iniciando o projeto node
```
npm init -y
```
Instalando o typescript como dependência de desenvolvimento
```
npm i typescript -D
```
```
npm i @types/node -D
```
Criando o arquivo de sintax tsconfig do typescript
```
npx tsc --init
```
Modificar o "target" do arquivo "tsconfig.json" para "es2020"

Instalando o tsx como dependência de desenvolvimento
```
npm i tsx -D
```
Instalando o framework fastify
```
npm i fastify
```
Instalando o eslint como dependência de desenvolvimento
```
npm i eslint -D
```
Instalando a configuração da Rocketseat
```
npm i @rocketseat/eslint-config -D
```
Criar o arquivo ".eslintrc.json" na raiz do projeto, e adicionar as linhas:
```
{
  "extends": [
    "@rocketseat/eslint-config/node"
  ]
}
```
Instalando o prisma como dependencia de desenvolvimento
```
npm i prisma -D
```
Instalando plugin SQLite
```
npx prisma init --datasource-provider SQLite
```
Comando de criação de tabela com o prisma
```
npx prisma migrate dev
```
Instalando o @prisma/client
```
npm i @prisma/client
```



-----old project

Instalar o @fastify/cors (mecanismo de segurança que valida quem pode consumir ou não a API)
```
npm i @fastify/cors
```
Comando para vizualizar o banco de dados pelo prisma no navegador
```
npx prisma studio
```
Instalando ERD Generator como dependencia de desenvolvimento
```
npm i prisma-erd-generator @mermaid-js/mermaid-cli -D
```
Inserir este codigo no schema.prisma<br>
<img align="center" title="Printscreen" src="https://github.com/ur4sh1/SERVER-Setup---NLW-Rocketseat/blob/main/printscreen/erd_generator.png" /><br>
Executar o erd generator
```
npx prisma generate
```
Criando o arquivo 'seed' para polular o banco<br>
<img align="center" title="Printscreen" src="https://github.com/ur4sh1/SERVER-Setup---NLW-Rocketseat/blob/main/printscreen/seed.png" /><br>
Adicionando configuração no package.json para uso do seed pelo prisma
```
"prisma": {
  "seed": "tsx prisma/seed.ts"
}
```
Executando o seed
```
npx prisma db seed
```
Instalando o zod (schema validation)
```
npm i zod
```
Instalando a biblioteca dayjs
```
npm i dayjs
```


Instalando o short-unique-id (gerador de id's únicos)
```
npm i short-unique-id
```
Instalando o node-fetch
```
npm i node-fetch
```
Instalando jwt
```
npm i @fastify/jwt
```

## :wrench: Docker
Building image
```
docker build -t api-setup .
```
Run container in docker
```
docker run -d -p 3333:3333 --name api-setup api-setup
```