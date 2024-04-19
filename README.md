# Atividade-BankAPI

# BankAPI v4

## Resumo
Este projeto implementa um sistema bancário com operações de saque, depósito, transferência e gerenciamento de contas.

## Funcionalidades
- Transações validam valores positivos.
- Métodos CRUD para contas bancárias.

## Testes
Testes asseguram que transações não processam valores negativos.

## Camadas
- `TransactionService`: Testes para `withdraw` e `transfer`.
- `AccountService`: Testes para `getByNumber`, `getAll`, `save` e `update`.
- `TransactionController` e `AccountController`: Testes para operações e respostas HTTP.

## Validações
- `AvailableAccountValidation`: Verifica a existência de contas.
- `AvailableBalanceValidation`: Checa saldo suficiente para transações.

## Notas
- Não é possível realizar saques ou transferências com valores negativos.
