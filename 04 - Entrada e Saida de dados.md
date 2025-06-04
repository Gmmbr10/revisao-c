# Entrada e Saída de dados

Ok, até agora você aprendeu a como declarar uma variável e os tipos de dados.
Mas como fazemos para pedir e receber os dados?

Esses processos chamamos de entrada e saída de dados.

## Saída de dados

Para exibir uma mensagem ao usuário, usamos o comando `printf("Mensagem");`, dessa forma:

```C

#include<stdio.h>

int main(){
  printf("Mensagem que será exibida ao usuário \n");
  return 0;
}

```

> `\n`: um código que pode ser usado em textos usado para quebrar a linha

## Entrada de dados

Para receber um dado enviado pelo usuário, usamos o comando `scanf();`, dessa forma:

```C

#include<stdio.h>

int main(){
  int idade;
  scanf("%d",&idade);
  return 0;
}

```

A entrada de dados possuí dois itens:

- O primeiro indica o **código de formatação** do dado enviado
- O segundo o endereço da variável
  - > Esse segundo parâmetro é composto pelo símbolo `&` e logo em seguida, sem espaço, pelo nome da variável
  - > Eles juntos, formam o endereço da variável

> **Parâmetro**: variável passada para uma função

### Códigos de formatação

Aqui vai uma tabela dos códigos e dos tipos de dados:

| Código | Tipo de dado |
| --- | --- |
| `%d` | int |
| `%f` | float |
| `%lf` | double |
| `%c` | char |
| `%s` | palavra |

## Exibindo variáveis

Para exibir variáveis, usamos os códigos de formatação dentro da mensagem.
E as variáveis na sequência de exibição, como parâmetros fora das aspas e separados por vírgula.

Dessa forma:

```C
#include<stdio.h>

int main(){
  int idade = 20;
  printf("Este usuário tem %d anos de idade \n",idade);
  return 0;
}
```

Ir para: <a href="./05 - Operadores.md">05 - Operadores</a>