# Backend Rocket Movies

Este é o backend do projeto "Rocket Movies", um sistema de gerenciamento de filmes. Este backend é responsável por lidar com a lógica de negócios e interações com o banco de dados.

## Funcionalidades

- Listagem de filmes
- Detalhes de filmes
- Adição de novos filmes
- Atualização de informações de filmes
- Remoção de filmes

## Tecnologias Utilizadas

- Node.js
- Express.js
- Knex.js
- SQLite (ou o banco de dados de sua escolha)

## Setup

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Clone este repositório: `git clone https://github.com/seu-usuario/backend-rocket-movies.git`
3. Navegue até o diretório do projeto: `cd backend-rocket-movies`
4. Instale as dependências: `npm install`
5. Configure o banco de dados no arquivo `knexfile.js`
6. Execute as migrações do banco de dados: `npx knex migrate:latest`
7. Inicie o servidor: `npm start`
8. O servidor estará disponível em `http://localhost:3000`
