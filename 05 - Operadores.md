# Operadores

Temos diferentes tipos de operadores, aqui vai alguns deles:

## Operadores de atribuição

Utilizados para atribuir valores às variáveis.

Sendo o mais famoso o `=`, que representa igual (ou recebe).

## Operadores aritméticos

Utilizados para realizar operações matemáticas

Sendo eles:

| Operador | Nome | Função |
| --- | --- | --- |
| `+` | Soma | Realiza a operação de adição |
| `-` | Subtração | Realiza a operação de subtração |
| `/` | Divisão | Realiza a operação de divisão |
| `*` | Multiplicação | Realiza a operação de multiplicação |
| `%` | Resto de divisão (módulo) | Pega o valor que sobra de uma divisão |
| `++` | Incremento (Sucessor) | Realiza a operação de adicionar 1 unidade do valor da variável |
| `--` | Decremento (Antecessor) | Realiza a operação de retirar 1 unidade do valor da variável |

### Exemplos

```C

#include<stdio.h>

int main(){
  int soma = 1 + 1;           // soma = 2
  int subtracao = 2 - 1;      // subtracao = 1
  int multiplicacao = 2 * 3;  // multiplicacao = 6
  int divisao = 4 / 2;        // divisao = 2
  int resto = 3 % 2;          // resto = 1
  int numero = 5;
  numero++;                   // numero = 6
  numero--;                   // numero = 5
  return 0;
}

```

## Operador relacionais

Usados em condições para comparar valores.

São eles:

| Operador | Nome / função |
| --- | --- |
| `>` | Maior que |
| `>=` | Maior ou igual que |
| `<` | Menor que |
| `<=` | Menor ou igual que |
| `==` | Igual |
| `!=` | Diferente |

## Operadores lógicos

Usados para adicionar condições

| Operador | Nome | Função |
| --- | --- | --- |
| `&&` | E | Ambas as condições tem que ser verdadeiras |
| `\|\|` | Ou | Apenas uma das condições tem que  |
| `!` | Não | Inverte o valor booleano |

Ir para: <a href="./06 - Estrutura Condicional.md">06 - Estrutura Condicional</a>