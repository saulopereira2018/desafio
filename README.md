Sistema Bancário Simples
Este é um sistema bancário simples, desenvolvido em Python, que simula operações de depósito, saque e consulta de extrato de um cliente.

Funcionalidades
O sistema oferece as seguintes opções de operação:

[d] Depositar: Permite o depósito de um valor na conta.
[s] Sacar: Permite o saque de um valor da conta (com limite de saques e verificação de saldo disponível).
[e] Extrato: Exibe o extrato das operações realizadas até o momento, incluindo depósitos e saques.
[q] Sair: Finaliza o programa.
Regras de Operação
Depósito: O valor deve ser positivo para que o depósito seja efetuado com sucesso. O valor depositado será exibido no extrato.

Saque:

O valor do saque não pode ultrapassar o saldo disponível.
O valor do saque não pode exceder o limite diário de R$ 500,00.
O número máximo de saques permitidos por dia é 3.
O valor do saque também deve ser positivo.
Extrato: Exibe todas as operações realizadas até o momento (depósitos e saques). Se nenhuma operação foi realizada, o sistema informa que não há movimentações.
