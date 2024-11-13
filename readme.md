#include <stdio.h>
int main() {
    int idade;

    printf("Digite a idade do nadador: \n");
    scanf("%d", &idade);

    if (idade >= 0 && idade <= 16) {
        printf("Categoria: INFANTO-JUVENIL\n");
    } else if (idade >= 17 && idade <= 30) {
        printf("Categoria: ADULTO\n");
    } else if (idade >= 30) {
        printf("Categoria: SENIOR\n");
    } else {
        printf("Idade inválida.\n");
    }
     
	 return 0;
}