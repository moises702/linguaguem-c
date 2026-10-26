#include <stdio.h>
int main() {
    
    int opcao;
    int dinheiro = 0;
    
    do{
        printf("1 - Adicionar R$ 0,50\n");
        printf("2 - Adicionar R$ 1,00\n");
        printf("3 - Adicionar R$ 2,00\n");
        printf("0 - Parar e mostrar o resultado:\n");
        scanf("%d", &opcao);
        
        if (opcao == 1) {
            dinheiro += 50;
        } else if (opcao ==2) {
            dinheiro += 100;
        } else if (opcao ==3) {
            dinheiro += 200;
        }
    } while (opcao != 0);
    
    printf ("Valor acumulado: R$ %.2f\n", dinheiro / 100.0);
    
    return 0;
}
