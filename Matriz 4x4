#include <stdio.h>
#include <stdlib.h>

int main()
{

   int md[4][4] = {{00,999,10,999},{999,00,15,20},{10,15,00,999},{999,20,999,00}};
   int lin, col;
   int distancia;
   int aux=0;

   for(lin=0;lin<4;lin++){
      for(col=0;col<4;col++)
      {     
            printf(" [%.2d] ", md[lin][col]);
      }
      printf("\n");    
   }
	
   for(lin=0;lin<4;lin++)
   {
         for(col= 0;col<4;col++)
         { 
         printf("\n\n Informe o numero da linha da primeira cidade: ");
         scanf("%d", &lin); 
         printf("Informe o numero da coluna da segunda cidade: ");
         scanf("%d", &col);

         distancia = md[lin][col];

         if (md[lin][col] == 0)
         {
         printf("\n voce ja esta nesta cidade");
         return 0;
         }
         
          if (md[lin][col] == 999)
         {
         printf("\n Nao ha ligacao direta entre essas cidades");
         return 0;
         }


         printf("\n A distancia entre a cidade %d e a cidade %d e: %d km", lin, col, distancia);                                         
         }
   	}       

system ("pause");
return 0;           
}
