# Sistema de Inventário usando Node.js, EJS, Express, Sequelize e SQL

Este projeto consiste em um sistema de inventário desenvolvido utilizando Node.js, EJS (Embedded JavaScript), Express, Sequelize (um ORM para SQL) e SQL como banco de dados. O objetivo deste sistema é gerenciar o estoque de uma empresa de forma eficiente e organizada.

## Funcionalidades do Sistema

- Cadastro, visualização, atualização e exclusão de produtos.
- Gerenciamento de categorias e fornecedores.
- Controle de entrada e saída de produtos.
- Relatórios de estoque, movimentação de produtos e desempenho de fornecedores.

## Estrutura do Projeto

O projeto possui a seguinte estrutura de arquivos e diretórios:

- `app.js`: Arquivo principal que configura e inicializa a aplicação Express.
- `config/`: Diretório contendo arquivos de configuração, como configurações do banco de dados.
- `controllers/`: Diretório contendo controladores que definem o comportamento das rotas.
- `models/`: Diretório contendo modelos Sequelize para representar as tabelas do banco de dados.
- `public/`: Diretório contendo arquivos estáticos, como CSS, JavaScript e imagens.
- `routes/`: Diretório contendo definições de rotas da aplicação Express.
- `views/`: Diretório contendo arquivos EJS para as visualizações da aplicação.
- `migrations/`: Diretório contendo arquivos de migração do Sequelize para controlar alterações no banco de dados.

## Como Executar o Projeto

1. Clone o repositório para sua máquina local.
2. Certifique-se de ter o Node.js e npm instalados em seu ambiente.
3. Execute `npm install` na raiz do projeto para instalar as dependências.
4. Configure as informações do banco de dados no arquivo `config/database.js`.
5. Execute as migrações do Sequelize para criar as tabelas no banco de dados: `npx sequelize-cli db:migrate`.
6. Inicie a aplicação com o comando `npm start`.
7. Acesse a aplicação em seu navegador através do endereço `http://localhost:3000`.

## Personalização

Você pode personalizar este sistema de inventário de acordo com as necessidades da sua empresa. Algumas sugestões de personalização incluem:

- Adicionar novas funcionalidades, como controle de lote, controle de validade de produtos, entre outros.
- Personalizar a aparência da interface do usuário para atender à identidade visual da sua empresa.
- Implementar autenticação de usuários para controlar o acesso às funcionalidades do sistema.

## Contribuindo

Este projeto é de código aberto e as contribuições são bem-vindas. Sinta-se à vontade para abrir problemas relatando bugs, sugerir novas funcionalidades ou enviar solicitações de pull requests para melhorar o sistema.

Esperamos que este sistema de inventário seja útil para gerenciar o estoque da sua empresa de forma eficiente e organizada. Boa sorte e aproveite!
