# Logica-da-programa-o-em-C-

Este repositório contém exercícios básicos de **lógica de programação** utilizando a linguagem **C**.

## Conteúdo
- Estruturas de decisão (`if`, `else`, `switch`)
- Estruturas de repetição (`for`, `while`, `do-while`)
- Entrada e saída de dados (`scanf`, `printf`)
- Exercícios práticos do cotidiano

## Objetivo
Praticar a lógica e consolidar a base da programação em C.

## Como executar
```bash
## 📄 main.c
```c
#include <stdio.h>

int main() {
    int numero;
    printf("Digite um número: ");
    scanf("%d", &numero);

    if (numero % 2 == 0)
        printf("Número par!\n");
    else
        printf("Número ímpar!\n");

    return 0;
}
