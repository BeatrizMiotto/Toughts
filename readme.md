# Thoughts

Uma aplicação Node.js para gerenciamento de pensamentos.

## Descrição:
Aplicação web desenvolvida durante o curso da Udemy, utilizando Node.js e diversas bibliotecas para oferecer funcionalidades de autenticação, criação, edição, exclusão e busca de pensamentos.

## Pacotes utilizados:
* Express.js
* Handlebars
* Sequelize (ORM para MySQL)
* bcryptjs (criptografia de senhas)
* connect-flash, cookie-parse, cookie-session, express-flash, express-session, session-file-store (gerenciamento de sessões)
* mysql2 (driver para MySQL)
* nodemon (reinicia o servidor automaticamente)

## Funcionalidades:
* Autenticação: Criação de contas, login e logout.
* Pensamentos:
 * Criação de novos pensamentos.
 * Edição de pensamentos existentes.
 * Exclusão de pensamentos.
 * Busca de pensamentos por palavras-chave.
 * Rotas Protegidas: Acesso restrito a funcionalidades para usuários autenticados.

