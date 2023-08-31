# APP

Serviço de gerenciamento de transações financeiras.

Utilizando as seguintes tecnologias:
- fastify -> Framework que permite que criação de servidores REST;
- typescript -> Linguagem de programação tipada;
- knex -> Query-builder para consultas em banco de dados relacional;
- vitest -> Testes da aplicação;
- eslint -> Padrão de código;
- tsup -> Build da aplicação;
- cookie -> Gerenciamento de sessões;

# Requisitos da aplicação

## RFs (Requisitos funcionais)

- [X] O usuário deve poder criar uma nova transação;
- [X] O usuário deve poder obter um resumo da sua conta;
- [X] O usuário deve poder listar todas transações que já ocorreram;
- [X] O usuário deve poder visualizar uma transação única;

## RNs (Regras de negócio)

- [X] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [X] Deve ser possível identificarmos o usuário entre as requisições;
- [X] O usuário só pode visualizar transações o qual ele criou;
