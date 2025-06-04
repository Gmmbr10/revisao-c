# Estrutura de repetição

Estruturas de repetição são utilizados para executar um determinado código enquanto uma condição for verdadeira.

Vejamos elas:

## For

```C

#include<stdio.h>

int main(){
  int contador;

  /*
  for ( declara o contador ; condicao ; incrementa o contador ) {

    código

  }
  */

  for ( contador = 1 ; contador <= 10 ; contador = contador + 1 ) {

    printf("Olá mundo");

  }

  return 0;
}

```

## While

```C

#include<stdio.h>

int main(){
  int contador;

  /*
  while ( condicao ) {

    código

  }
  */

  contador = 1;

  while ( contador <= 10 ) {

    printf("Olá mundo");

    contador = contador + 1;

  }

  return 0;
}

```

## Do - While

```C

#include<stdio.h>

int main(){
  int contador;

  /*
  do {

    código

  } while ( condicao );
  */

  contador = 1;

  do {

    printf("Olá mundo");

    contador = contador + 1;

  } while ( contador <= 10 );

  return 0;
}

```

# Diferenças

A principal diferença é a sintaxe, o que mais se diferencia de todos é o `do-while`.

O `do-while` executa o código antes de testar a condição.

Então tome cuidado ao utiliza-lo.