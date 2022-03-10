# Crie-um-algoritmo-que-receba-5-notas-e-retorne-a-media-das-5-
#include <stdio.h>
#include <stdio.h>

int main(void)
{
 //Crie um algoritmo que receba 5 notas e retorne a média das 5 
 
int cont;

float nota, media, total;

total = 0;

for (cont = 1; cont <=5; cont++) {
 printf("Digite a nota:");
 
  scanf("%f", &nota);
   
   total = total + nota;
   
}

media = total / 5;

printf("Nota media:%.2f\n",media);
  
  return 0;
}


