# Resolução Exercicio24_while

## Descrição do problema
Escreva um programa em Java que mostre todos os números pares entre 13 e
23 usando do..while.

## Como Funciona
1. O algoritmo define o ponto de partida na variável `i = 14`, correspondente ao primeiro número par válido dentro da faixa solicitada (já que 13 é um número ímpar).
2. A estrutura `do { ... } while (condição)` garante que o bloco interno seja executado pelo menos uma vez antes de testar a condição de parada:
   - A instrução `System.out.println(i)` imprime o número par corrente no console.
   - A variável de controle é incrementada de duas em duas unidades (`i += 2`) de forma direta, saltando de um par para o próximo e otimizando o processamento.
3. O laço se repete continuamente enquanto a condição `i < 23` permanecer verdadeira.