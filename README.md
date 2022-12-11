#include <stdio.h>
#include <stdlib.h>
  int main(int argc, char* argv[]) {  
  
  float valor, perc, total_valor;
  
  printf("o valor da conta: ");  
  
  scanf("%f", &valor);    
  
  printf("a percentagem do garcom: ");   
  
  scanf("%f", &perc);   
  
  total_valor = valor*perc/100;  
  
  printf("valor do garcom e: %.2f",total_valor); 
  
  system("pause");   
  return 0;
  }
