# Descrição do Código

Este código implementa um simples sistema bancário com funcionalidades de depósito, saque e exibição de extrato. Abaixo estão as seções principais do código:

## Menu de Opções

O código começa definindo um menu de opções que permite ao usuário escolher entre depositar, sacar, ver o extrato ou sair do programa.

## Variáveis Globais

São definidas variáveis globais para armazenar o saldo, limite de saque, extrato das transações, número de saques realizados e o limite de saques permitidos por dia.

## Função `depositar`

Esta função recebe um valor como parâmetro, adiciona esse valor ao saldo e registra a transação no extrato.

## Função `sacar`

Esta função recebe um valor como parâmetro, subtrai esse valor do saldo, registra a transação no extrato e incrementa o contador de saques realizados.

## Função `mostrar_extrato`

Esta função exibe todas as transações registradas no extrato e o saldo atual. Se não houver transações, informa que não foram realizadas movimentações.

## Loop Principal

O código entra em um loop infinito onde:
- Solicita ao usuário que escolha uma opção do menu.
- Dependendo da opção escolhida, chama a função correspondente (`depositar`, `sacar` ou `mostrar_extrato`).
- Verifica condições como saldo insuficiente, limite de saque excedido e limite de saques diários.
- Permite ao usuário sair do programa escolhendo a opção "0".

## Tratamento de Erros

O código inclui verificações para garantir que os valores de depósito e saque sejam válidos e que as operações respeitem os limites definidos.

## Finalização do Programa

O loop principal pode ser interrompido quando o usuário escolhe a opção de sair, exibindo uma mensagem de fim de programa.
