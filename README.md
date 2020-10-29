# Projeto - Ocean Backend Cloud - (Node.js + MongoDB + Heroku)
Projeto realizado nas aulas de Backend no Ocean Samsung (27/10/2020 e 29/10/2020). 
Objetivo: trabalhar a construção de APIs REST usando Node.js Express fazendo conexão com o Banco de dados MongoDB. Integrar a API construída nas outras aulas com os serviços de backend na nuvem, utilizando o Heroku, o MongoDB Atlas e NoSQLBooster.

Projeto original do prof Paulo Salvatore: https://github.com/paulosalvatore/Ocean_Backend_Cloud_29_10_2020

# Ferramentas utilizadas:
1. VSCode
2. MongoDB Atlas
3. Postman
4. Heroku
5. NoSQLBooster 

# Dependências utilizadas:
1. Express
2. Nodemon
3. Body-parser
4. MongoDB driver

# Instalação e configuração do projeto

 No terminal, digite o comando `npm install`  para a instalação do projeto. Note que isso criará a pasta `node_modules`
 Para rodar, digite no terminal o comando `node index`. Isso iniciará o servidor na rota `http://localhost:3000`

# Configuração de ambiente em Cloud
1. Certifique-se de que possui instalado os seguintes programas:
    1. NoSQLBooster: https://nosqlbooster.com/downloads
    2. NodeJS: https://nodejs.org/en/download/
2. Criar conta no Heroku e fazer login;
3. Criar conta no MongoDB Atlas e fazer login;
4. Pode colocar a linguagem `Node` ou `JavaScript` no Heroku/Atlas, só serve para pesquisa deles;
5. O heroku é a plataforma em nuvem que vamos utilizar para hospedar nosso projeto backend em NodeJS;
6. O MongoDB Atlas é a plataforma de banco de dados em nuvem para hospedar um banco MongoDB;
7. No Heroku, clica na opção `New` e depois em `Create new app`;
8. Coloque o nome do app, mantém United States e clica em criar;
9. Na aba de `Deploy`, procura pela parte de `Deployment method` e clica na opção `GitHub`;
10. Faça a conexão com o GitHub;
11. Precisa aparecer a opção `Search for a repository to connect to`;
12. Digite o nome do projeto, clique em Search, buque-o na lista e clique em `Connect`;
13. Selecione a branch principal, no meu caso chama main e clique em `Enable Automatic Deploys`;


