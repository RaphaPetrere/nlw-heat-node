# NLW Heat - Node Backend

> Essa é uma versão inicial do README, somente para deixar anotado as coisas que foram feitas.

### Tecnologias Empregadas
- TypeScript
- JWT
- Socket.io
- Prisma ORM

### Comandos diferentes

- yarn prisma studio -> abre o Prisma Studio, como se fosse um sqlite studio, você consegue ver tabelas, as relações.

- yarn prisma migrate dev -> realiza a migration.

### Ações realizadas

- Autenticando pelo github
- Validando a autenticação no callback para criar o token com jwt
- Utilizando o prisma para a manipulação do DB
- Utilizando o socket.io para as mensagens