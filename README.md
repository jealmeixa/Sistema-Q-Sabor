# Q’Sabor 

Sistema de gerenciamento de lanchonetes em áreas estudantis, desenvolvido em Java para facilitar a realização de pedidos, pagamentos e retirada de produtos pelos estudantes.

## Informações acadêmicas

- **Universidade:** Universidade de Mogi das Cruzes (UMC)
- **Curso:** Engenharia de Software
- **Turma:** 5B
- **Disciplina:** Padrões de Projeto
- **Professor:** Pedro

### Integrantes

- Estefani Bianca — 11262401727
- Jennifer Almeida — 11261105454
- Thaís Lorrany — 11262400223

---

## Objetivo

Desenvolver um sistema de lanchonetes em áreas estudantis utilizando Java, com operações de CRUD e aplicação dos Design Patterns DAO, MVC, Command, Factory Method, Builder e Decorator, permitindo o cadastro de clientes, a realização de pedidos e pagamentos, além de agilizar o processo de retirada na lanchonete.

## Descrição do sistema

O sistema será desenvolvido para facilitar a vida dos estudantes, permitindo o cadastro de clientes, a escolha de produtos e adicionais, a realização de pedidos e pagamentos, além da retirada dos pedidos diretamente na lanchonete, proporcionando mais praticidade e agilidade no atendimento.

## Requisitos funcionais e dados do sistema

### Cliente
- ID do cliente;
- Nome;
- E-mail;
- CPF;
- RGM;
- Senha.

### Item do pedido
- ID do item;
- Tipo;
- Quantidade;
- Valor.

### Pedido
- ID do pedido;
- CPF;
- Quantidade;
- Data;
- Valor total.

### Pagamento
- ID do pagamento;
- ID do pedido;
- Data do pagamento;
- Valor total.

## Automação do pagamento

O sistema contará com uma funcionalidade para automatizar o processo de pagamento dos pedidos realizados pelos estudantes. Nele, será possível consultar o valor total do pedido e registrar o pagamento.

Após a confirmação do pagamento, o pedido será identificado como pago e ficará disponível para retirada na lanchonete.

Dessa forma, o sistema facilitará o controle dos pedidos e pagamentos, tornando o processo mais rápido, organizado e eficiente para os estudantes e funcionários.







