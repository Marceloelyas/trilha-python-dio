

# Sistema Bancário em Python

Este é um sistema bancário simples implementado em Python que permite operações básicas como depósitos, saques, visualização de extrato, criação de usuários e contas bancárias.

# Funcionalidades

- Depósito: Adiciona valores à conta do usuário

- Saque: Retira valores da conta (com limites diários)

- Extrato: Exibe o histórico de transações e saldo atual

- Criação de usuário: Cadastra novos clientes no sistema

- Criação de conta: Associa contas bancárias aos usuários existentes

- Listagem de contas: Mostra todas as contas cadastradas no sistema

# Requisitos

- Python 3.x

# Como Executar

1- Clone o repositório ou copie o código para um arquivo .py

2- Execute o arquivo com Python:

bash

python trilha-python-dio.py

# Estrutura do Código

O sistema está organizado nas seguintes funções:

- menu(): Exibe o menu de opções

- depositar(): Realiza operações de depósito

- sacar(): Realiza operações de saque (com validações)

- exibir_extrato(): Mostra o histórico de transações

- criar_usuario(): Cadastra novos usuários

- filtrar_usuario(): Busca usuários por CPF

- criar_conta(): Cria novas contas bancárias

- listar_contas(): Lista todas as contas existentes

- main(): Função principal que orquestra todo o sistema

# Limitações

- Os dados são armazenados apenas em memória (não persistem após encerrar o programa)

- Limite de 3 saques diários

- Limite de R$ 500,00 por saque

# Melhorias Possiveis Futuras

- Persistência de dados em arquivo ou banco de dados

- Implementação de senhas e autenticação

- Adição de mais operações bancárias (transferências, investimentos, etc.)

- Interface gráfica ou web

# Autor

Marcelo Elyas.

# Licença
