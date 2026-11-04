# Particionando Números com Streams

Projeto desenvolvido em Java para praticar o uso da Stream API.

## 📚 Conceitos utilizados

- List
- Map
- Arrays.asList()
- Stream API
- Collectors.partitioningBy()
- Lambda Expressions

## 💻 Funcionamento

O programa cria uma lista de números inteiros e utiliza
`partitioningBy()` para dividir os números em dois grupos:

1. Números pares.
2. Números ímpares.

A condição utilizada verifica se o resto da divisão
por 2 é igual a zero.

## ▶️ Exemplo de saída

```text
Pares: [2, 4, 6]
Ímpares: [1, 3, 5]
