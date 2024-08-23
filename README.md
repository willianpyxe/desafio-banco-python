# 🏦 Sistema Bancário em Python

Este projeto é uma implementação simples de um sistema bancário em Python que permite ao usuário realizar operações básicas, como depósito, saque e visualização de extrato.

## 🚀 Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **💰 Depósito**: O usuário pode depositar qualquer valor positivo em sua conta.
- **🏧 Saque**: O usuário pode realizar até três saques diários, com um limite máximo de R$ 500,00 por saque.
- **📄 Extrato**: O usuário pode visualizar o extrato de todas as transações realizadas, incluindo depósitos e saques, além do saldo atual da conta.

## 📋 Regras de Negócio

1. **💸 Depósito**:
   - Somente valores positivos são permitidos.
   - O valor do depósito é somado ao saldo e registrado no extrato.

2. **💳 Saque**:
   - Limite de até três saques diários.
   - O valor máximo por saque é de R$ 500,00.
   - O saque só é permitido se o saldo for suficiente.
   - Todos os saques são registrados no extrato.

3. **📜 Extrato**:
   - Lista todas as operações de depósito e saque.
   - Exibe o saldo atual da conta.

## 🛠️ Exemplo de Uso

Ao executar o programa, o usuário verá o seguinte menu:


- **💰 Depositar**: Escolha a opção `d` e insira o valor que deseja depositar.
- **🏧 Sacar**: Escolha a opção `s` e insira o valor que deseja sacar, respeitando as regras de saque.
- **📄 Extrato**: Escolha a opção `e` para visualizar o extrato de todas as transações.
- **🚪 Sair**: Escolha a opção `q` para encerrar o programa.

## 🖥️ Pré-requisitos

- Python 3.x

## ▶️ Como Executar

1. Clone o repositório ou baixe o arquivo `sistema_bancario.py`.
2. Execute o script com Python:

   ```bash
   python sistema_bancario.py
