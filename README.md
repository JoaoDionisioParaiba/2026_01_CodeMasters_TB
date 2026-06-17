#include <stdio.h>

// #include "funcao_soma.h"          
// #include "funcao_subtracao.h"     
// #include "funcao_multiplicacao.h" 
#include "funcao_divisao.h"       

int main() 
{
    printf("Bem-vindo ao nosso projeto de calculadora do Grupo CodeMasters!\n");
    printf("Integrantes: Breno, César, Daniel, Lucas\n");
    printf("Funcoes planejadas: Soma, Subtracao, Multiplicacao, Divisao\n\n");
      
    float resultado_divisao = dividir(100.0, 4.0);
    printf("Divisao (100.0 / 4.0): %.2f\n", resultado_divisao);

    float resultado_divisao_erro = dividir(10.0, 0.0);
    printf("Divisao (10.0 / 0.0): %.2f\n", resultado_divisao_erro);
    
    return 0;
