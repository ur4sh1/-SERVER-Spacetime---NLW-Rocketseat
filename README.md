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
Instalando o zod (schema validation)
```
npm i zod
```
Instalando cors
```
npm i @fastify/cors
```
