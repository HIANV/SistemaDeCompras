# SistemaDeCompras
Este código em Java simula uma compra simples. O usuário adiciona produtos ao carrinho, e o programa exibe o total acumulado. Composto pelas classes `Produto` (nome e preço) e `SimulacaoCompra` (interação), ele permite adicionar itens e encerrar a compra, exibindo um resumo final. Expansões incluem descontos, impostos e remoção de itens, em java
# Simulação de Compra em Java

Este projeto é uma simulação simples de compra em console, escrita em Java, que permite ao usuário adicionar produtos a um carrinho, visualizar o total da compra e finalizar a sessão com um resumo de itens.

## Funcionalidades

- Adicionar produtos ao carrinho com nome e preço.
- Exibir o valor total acumulado da compra.
- Finalizar a compra, mostrando um resumo dos itens e o valor total.

## Estrutura do Projeto

O código é composto por duas classes principais:

- **Produto**: Representa cada item do carrinho com `nome` e `preco`.
- **SimulacaoCompra**: Contém a lógica principal do programa, incluindo a interação com o usuário para adicionar produtos, calcular o total e exibir o resumo.

## Exemplo de Uso

```plaintext
Bem-vindo à Simulação de Compra!
Digite o nome do produto ou 'finalizar' para encerrar: Livro
Digite o preço do produto: 49.90
Produto adicionado: Livro - R$49.90
Total atual: R$49.90
Digite o nome do produto ou 'finalizar' para encerrar: Caneta
Digite o preço do produto: 2.50
Produto adicionado: Caneta - R$2.50
Total atual: R$52.40
Digite o nome do produto ou 'finalizar' para encerrar: finalizar

Resumo da Compra:
- Livro: R$49.9
- Caneta: R$2.5
Total da compra: R$52.4
Obrigado pela compra!
