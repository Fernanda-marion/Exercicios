# T003-Lista-Exercicio 1

A)

#include <stdio.h>

    int main () { 
     
float numero;
 
  numero = 4000000000;
  scanf ("%f",&numero);
  
return 0;

}

B)

#include <stdio.h>

    int main () {
        
    char a;
    
    scanf("%c",&a)
    
  
 return 0;
    }


C)

#include <stdio.h>

    int main () {
        
        int numero1,numero2,multi;
        
   printf ("Digite o primeiro numero:");
   scanf("%d",&numero1);
   
   printf ("Digite o segundo numero:");
   scanf("%d",&numero2);
   
   multi=(numero1*numero2);
   
   printf("A multiplicaçao dos dois numeros digitados e: %d",multi);
   
   return 0;
   
    }

D)

#include <stdio.h>

    int main () {
        
        char letra;
        
        printf("Informe a letra:");
        scanf("%c",&letra);
        if(letra=='a'){
            printf("Voce escolheu a letra a");
        }
        else(letra!='a');{
            printf("Letra invalida");
        }
        
   return 0;
   
    }





