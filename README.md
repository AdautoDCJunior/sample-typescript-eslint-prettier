> # Exemplo Typescript, ESLint, Prettier
> Repósito de um exemplo de aplicação utilizando typescript com eslint e prettier.

##

> ### Comandos instalação:
>
> #### `yarn add -D typescipt`
> Comando de instalação do typescript.
>
> #### `yarn tsc --init`
> Comando para gerar o arquivo de configuração do typescript (tsconfig).
>
> #### `yarn add -D eslint`
> Comando para instalar o ESLint.
>
> #### `yarn eslint --init`
> Comando para instalar as dependências e o arquivo de configuração do eslint (.eslintrc).
>
> #### `yarn add -D prettier eslint-config-prettier eslint-plugin-prettier`.
> Comando para instalar o Prettier e suas dependências.
>
> #### `yarn add -D nodemon ts-node`
> Comando para instalar o nodemon e o ts-node.

##

> ### Scripts:
>
> #### `yarn start`
> Esse comando irá formatar, fazer a verificação ESLint, compilar para JS e executar o arquivo `index.js`da pasta `dist`.
>
> #### `yarn dev`
> Esse comando irá fazer a verificação ESLint, executar o arquivos `index.ts` da pasta `src` através do ts-node e o nodemons irá monitorar as alterações dos arquivos em tempo real.
>
> #### `yarn build`
> Esse comando irá compilar os arquivos para JS.
>
> #### `yarn lint`  
> Esse comando irá executar a verificação do ESLint.
>
> #### `yarn format`
> Esse comando irá executar a formatação do código utilizando as configurações do Prettier.

##
