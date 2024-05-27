# Plataforma de eBooks 📚

[![Node.js](https://img.shields.io/badge/Node.js-14.17.0-green)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.19.2-blue)](https://expressjs.com/)
[![EJS](https://img.shields.io/badge/EJS-3.1.9-orange)](https://ejs.co/)
[![MySQL](https://img.shields.io/badge/MySQL-2.18.1-blueviolet)](https://www.mysql.com/)
[![Sequelize](https://img.shields.io/badge/Sequelize-6.37.2-yellow)](https://sequelize.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-purple)](https://getbootstrap.com/)
[![Bootstrap Icons](https://img.shields.io/badge/Bootstrap%20Icons-1.11.3-blueviolet)](https://icons.getbootstrap.com/)
[![bcryptjs](https://img.shields.io/badge/bcryptjs-2.4.3-green)](https://www.npmjs.com/package/bcryptjs)

Plataforma de eBooks é uma aplicação para leitura e distribuição de livros digitais. Desenvolvida com tecnologias modernas, incluindo Node.js, Express.js, EJS, MySQL, Sequelize, Bootstrap, Bootstrap Icons e bcryptjs.

## Instalação

1. Clone este repositório.
2. Instale as dependências usando `npm install`.
3. Configure o banco de dados MySQL e as variáveis de ambiente.
4. Execute a aplicação usando `npm start`.
5. Acesse a plataforma em `http://localhost:3000`.

## Tabelas e Relações do Banco de Dados

### Tabela `categories`

Esta tabela armazena as categorias dos eBooks.

| Campo  | Tipo    | Descrição       |
|--------|---------|-----------------|
| title  | STRING  | Título da categoria |
| slug   | STRING  | Slug da categoria   |

### Tabela `comments`

Esta tabela armazena os comentários dos usuários sobre os eBooks.

| Campo        | Tipo    | Descrição           |
|--------------|---------|---------------------|
| comentario   | STRING  | Comentário do usuário |
| comentarioslug | STRING | Slug do comentário    |
| autor        | STRING  | Autor do comentário  |

### Tabela `e-books` (Books)

Esta tabela armazena informações sobre os eBooks.

| Campo  | Tipo    | Descrição       |
|--------|---------|-----------------|
| title  | STRING  | Título do eBook |
| slug   | STRING  | Slug do eBook   |
| capa   | TEXT    | URL da capa do eBook |
| body   | TEXT    | Corpo do eBook  |
| status | TEXT    | Status do eBook (por exemplo, publicado, rascunho, etc.) |

### Tabela `users`

Esta tabela armazena informações sobre os usuários.

| Campo    | Tipo    | Descrição          |
|----------|---------|--------------------|
| name     | STRING  | Nome do usuário    |
| apelido  | STRING  | Apelido do usuário |
| email    | STRING  | E-mail do usuário  |
| password | STRING  | Senha do usuário   |
| status   | STRING  | Status do usuário (por exemplo, ativo, inativo, etc.) |

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).


