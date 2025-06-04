# Variáveis e Tipos de dados

## Tipos de Dados

No mundo real, temos diversos tipos de dados, sejam eles textos ou números.

Na programação não será diferente.

Em C temos alguns tipos:

| Tipo | Explicação | Exemplo |
| --- | --- | --- |
| boolean | Verdadeiro ou falso | `true` ou `false` |
| char | Caracter | 'A' |
| int | Número inteiro | 10 |
| float | Número quebrado | 3.14 |
| double | Número quebrado de precisão dupla | 5.84 |
| void | Vazio |  |

> #### Na prática:
>
> - double: é mais preciso que o float, porém ocupa mais espaço na memória
> - void: usado quando não retornamos **nada**

### Importante

Cada tipo de dado ocupa um espaço diferente na memória.

Então quando for criar programas, pense bem o tipo de dado que você irá usar

## Variáveis

Variável é um espaço reservado na memória, RAM, que será usado para alocar um dado.

E como declaramos uma variável?

```C

#include<stdio.h>

int main() {
  // tipo_de_dado nome_da_variavel
  int idade;
  float pi;
  char alternativaCorreta;
  boolean alternativaEstaCorreta;
  return 0;
}

```

### Declarar Vs Inicializar

- **Declarar**: você cria a variável

- **Inicializar**: você atribuí um valor a variável

### Armazenando palavras

Uma palavra é um conjunto de caracteres, então, para declarar uma variável para armazenar palavras fazemos da seguinte forma:

```C

#include<stdio.h>

int main() {
  // char nome_da_variavel[quantidade máxima de letras]
  char nome[50]
  return 0;
}

```

## Como nomear uma variável?

Não podemos nomear as variáveis com qualquer nome.

Existem algumas regras para se nomear uma variável.

Aqui vão algumas regras:

- Não utilizar acentos
- Não utilizar caracteres especiais, exceto ( _ , $ )
- Não utilizar espaço entre as palavras, separe usando ( _ ) ou coloque a primeira letra da próxima palavra em maiúsculo
- Não pode iniciar com números, mas pode ter números

