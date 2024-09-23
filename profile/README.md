# Nome do projeto(Ainda a decidir)

## Sobre o projeto

Este projeto foi desenvolvido para concluir a matéria de Projeto Integrador II. Ele visa:
 - Facilitar a visualização do número de usuários e sessões em academias;
 - Permitir a classificação de um treino;
 - Controlar o tempo de treino de usuários.
   
## Requisitos

A máquina a ser instalada deve ter [Node.js](https://nodejs.org/en/download) instalado.
O navegador a ser utilizado deve ter JavaScript habilitado.

## Instalação

### API
Após clonar o repositório da [API](https://github.com/PI-II/api), criar um arquivo dentro da pasta ```src``` com o nome de ```db.js``` e, neste arquivo, inserir as configurações de banco:
 - Usuário;
 - Senha;
 - Host;
 - Tipo de banco.
   
Exemplo:
  ```js \
  const db = {
  "user": "root",
  "password": "pwd",
  "host": "localhost",
  "database": "mysql"
  }
  ```

Instalar as dependências da API com ```npm install```

Após isso, use ```cd src``` no terminal e inicie a api. Pode-se utilizar ```npx nodemon``` para que a API reinicie automaticamente a cada atualização ou ```node index.js``` para que ela inicie e seja reiniciada manualmente.

### Web

Após clonar o repositório do [Web](https://github.com/PI-II/web), abra o arquivo(com a API já iniciada).

