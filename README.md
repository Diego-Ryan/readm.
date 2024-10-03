# readm.
Estudos faculdade 
#include <stdio.h>
#include <stdlib.h>

int main() {
    int idade; // Changed to int for age
    printf("Digite sua idade: \n");
    
    // Check if input is valid
    if (scanf("%d", &idade) != 1) {
        printf("Por favor, insira um número válido.\n");
        return 1; // Exit with error code
    }

    if (idade > 20) {
        printf("Maior que 20.\n");
    } else {
        printf("20 ou menor.\n");
    }

    return 0;
}
