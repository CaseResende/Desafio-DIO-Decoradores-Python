# Desafio DIO Decoradores Python
 Desafio do curso de Python da DIO sobre Decoradores, Geradores e Iteradores.
 ---
## Tarefas
1. Implemente um **decorador** que seja aplicado a todas as funções de transações bancárias (depósito, saque, criação de conta, etc). Esse decorador deve registrar (printar) a data e hora de cada transação, bem como o tipo de transação.

2. Crie um **gerador** que permita iterar sobre as transações de uma conta e retorne, uma a uma, as transações que foram realizadas.
Esse gerador deve ter, também, uma forma de filtrar as transações baseado em seu tipo (por exemplo, apenas saques ou apenas depósitos).

3. Implemente um **iterador** personalizado _ContaIterador_ que permita iterar sobre todas as contas do banco, retornando informações básicas de cada conta (número, saldo atual, etc)
