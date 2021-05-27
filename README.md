## FinAPI - Financeira
  Sistema bancário parcial com cadastro de usuário, funções de depósito e saque e consultas de usuário e saldo. Demonstração de aplicação de funções e middlewares in Javascript.

---

### Requisitos

- [X] Deve ser possível criar uma conta
- [X] Deve ser possível buscar o extrato bancário do cliente
- [X] Deve ser possível realizar um depósito
- [X] Deve ser possível realizar um saque
- [X] Deve ser possível buscar o extrato bancário do cliente por data
- [X] De ser possível atualizar dados da conta do cliente
- [X] Deve ser possível obter dados da conta do cliente
- [X] Deve ser possível deletar uma conta
- [X] Deve ser possível pesquisar o saldo de uma conta

---

## Regras de negócio

- [X] Não deve ser possível cadastrar uma conta CPF já existente
- [X] Não deve ser possível buscar extrato em uma conta não existente
- [X] Não deve ser possível fazer depósito em uma conta não existente
- [X] Não deve ser possível fazer saque em uma conta não existente
- [X] Não deve ser possível fazer saque quando o saldo for insuficiente
- [X] Não deve ser possível excluir uma conta não existente