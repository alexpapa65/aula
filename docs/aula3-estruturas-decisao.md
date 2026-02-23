# Estruturas de Decisão na Lógica de Programação



As **estruturas de decisão** (ou condicionais) são blocos de controle que permitem ao programa executar diferentes trechos de código baseando-se em uma condição lógica. Elas permitem que o software "tome decisões" em tempo de execução.



---



## 1. A Condição (Booleana)

Toda estrutura de decisão baseia-se em uma expressão que resulta em apenas dois valores possíveis:

*   **Verdadeiro (True)**

*   **Falso (False)**



---



## 2. Tipos de Estruturas



### A. Estrutura Simples (`Se`)

Utilizada quando você quer que algo aconteça apenas se uma condição for satisfeita.

> **Exemplo:** Se o saldo for maior que o valor do saque, autorize a transação.



### B. Estrutura Composta (`Se - Senão`)

Define um caminho para o caso verdadeiro e um caminho alternativo para o caso falso.

```pseudocode

SE (idade >= 18) ENTÃO

&nbsp;   Escreva("Maior de idade")

SENÃO

&nbsp;   Escreva("Menor de idade")

FIM_SE




