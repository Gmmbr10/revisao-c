# Estrutura Condicional ou Estrutura de Seleção

Estruturas condicionais são códigos utilizatos para tomas decisões.

Essas estruturas podem ser:

## Estrutura condicional simples

Quando se testa uma condição e se ela é verdadeira, executa um determinado código.

```C

#include<stdio.h>

int main(){
  int valor = 1;

  /*
  if ( condicao ) {

    código

  }
  */

  if ( valor > 0 ) {

    printf("O valor é positivo");

  }

  return 0;
}

```

## Estrutura condicional composta

Quando se testa uma condição e se ela é verdadeira, executa um determinado código.

Caso não seja verdadeira, executamos outro código.

```C

#include<stdio.h>

int main(){
  int valor = 1;

  /*
  if ( condicao ) {

    código

  } else {

    código caso a condição seja falsa 

  }
  */

  if ( valor > 0 ) {

    printf("O valor é positivo");

  } else {

    printf("O valor é negativo");

  }

  return 0;
}

```

## Estrutura condicional encadeada

Quando se testa uma condição e se ela é verdadeira, executa um determinado código.

Caso não seja verdadeira, testamos outra condição. (esse passo pode ser quantas vezes for preciso)

Caso nenhuma das condições seja verdadeira, executa um código final.

```C

#include<stdio.h>

int main(){
  int valor = 1;

  /*
  if ( condicao ) {

    código

  } else {

    if () {

      código

    } else {

      código

    }
  }
  */

  if ( valor > 0 ) {
    
    printf("O valor é positivo");

  } else {

    if ( valor == 0 ) {

      printf("O valor é neutro");

    } else {

      printf("O valor é negativo");

    }

  }

  return 0;
}

```

Essa estrutura pode ser encontrada de uma maneira simplificada, ficando da seguinte forma:

```C

#include<stdio.h>

int main(){
  int valor = 1;

  /*
  if ( condicao ) {

    código

  } else if () {

    código

  } else {

    código

  }
  */

  if ( valor > 0 ) {
    
    printf("O valor é positivo");

  } else if ( valor == 0 ) {

    printf("O valor é neutro");

  } else {

    printf("O valor é negativo");

  }

  return 0;
}

```

## Estrutura de Seleção

Quando se tem valores precisos e queremos verificar se é correto.

Caso ele não seja preciso, executamos um código padrão.

Vejamos:

```C

#include<stdio.h>

int main(){
  int opcao;

  printf("Selecione uma operação:\n");
  printf("1. Adição\n");
  printf("2. Subtração\n");
  printf("3. Multiplicação\n");
  printf("4. Divisão\n");
  scanf("%d",&opcao);

  /*
  switch(variavel_a_ser_comparada){
    case valor:
      código
    break;
    [cases]
    default:
      código caso não seja uma opção válida
    break;
  }

  break - usado para sair do switch
  */

  switch(opcao){
    case 1:
      printf("Adição foi selecionado!");
    break;
    case 2:
      printf("Subtração foi selecionado!");
    break;
    case 3:
      printf("Multiplicação foi selecionado!");
    break;
    case 4:
      printf("Divisão foi selecionado!");
    break;
    default:
      printf("Opção inválida");
    break;
  }

  return 0;
}

```

Ir para: <a href="./07 - Estrutura de repeticao.md">07 - Estrutura de repetição</a>