#include <stdio.h>

// #include "funcao_soma.h"          
// #include "funcao_subtracao.h"    
#include "funcao_multiplicacao.h"
// #include "funcao_divisao.h"       

int main() 
{
    printf("Bem-vindo ao nosso projeto de calculadora do Grupo CodeMasters!\n");
    printf("Integrantes: Daniel, César, Hugo, Lucas\n");
    printf("Funcoes planejadas: Soma, Subtracao, Multiplicacao, Divisao\n\n");
      
    // O teste da soma fica comentado no seu computador:
    // int resultado_soma = somar(10, 5);
    // printf("Soma (10 + 5): %d\n", resultado_soma);
    
    // O teste da subtração fica comentado:
    // int resultado_subtracao = subtrair(20, 8);
    // printf("Subtracao (20 - 8): %d\n", resultado_subtracao);

    // Teste da sua função Multiplicar (Hugo) [cite: 168]
    int resultado_multiplicacao = multiplicar(7, 6); [cite: 37, 168]
    printf("Multiplicacao (7 * 6): %d\n", resultado_multiplicacao); [cite: 38]

    // O teste da divisão fica comentado:
    // float resultado_divisao = dividir(100.0, 4.0);
    // printf("Divisao (100.0 / 4.0): %.2f\n", resultado_divisao);
    
    return 0;
}
