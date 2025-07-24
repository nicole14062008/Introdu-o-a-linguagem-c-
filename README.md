[24/07, 18:51] Milaaa: a)
#include <stdio.h>
 #include <stdlib.h>           
int main() {
   printf("********** \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("*        * \n");
    printf("********** \n");
    //7 por 5
    printf(" *** \n");
    printf("*   * \n");
    printf("*   * \n");
    printf("*   * \n");
    printf("*   * \n");
    printf("*   * \n");
    printf(" *** \n");
    //9 por 7
    printf("    * \n");
    printf("   *** \n");
    printf("  ***** \n");
    printf(" ******* \n");
    printf("********* \n");
    printf("   * \n");
    printf("   * \n");
    //O losangulo
    printf("-------------\n");
    printf("      *    \n");
    printf("    *  *  \n");
    printf("   *    *");
    printf("  *      * \n");
    printf("   *    * \n");
    printf("    *  * \n");
    printf("      *") ;
  return 0;
}

c)
#include <stdio.h>
#include <stdlib.h>           

int main() {
    int num1, num2;  

    printf("Escreva o primeiro numero: ");
    scanf("%d", &num1);  

    printf("Escreva o segundo numero: ");
    scanf("%d", &num2);  

    return 0;
}



d)#include <stdio.h>
#include <stdlib.h>

int main() {
    int celsius;  

    
    printf("Informe a temperatura em Celsius: ");
    scanf("%d", &celsius);  

    
    printf("A temperatura informada foi: %d Celsius\n", celsius);

    return 0;
}


   

e)#include <stdio.h>
#include <stdlib.h>

int main() {
    int Fahreint;  

    
    printf("Informe a temperatura em Celsius: ");
    scanf("%d", &celsius);  

    
    printf("A temperatura informada foi: %d \n", celsius);

    return 0;
}




f)
#include <stdio.h>
#include <stdlib.h>           

int main() {
    int raio, altura;

    printf("Informe o valor do raio: ");
    scanf("%d", &raio);

    printf("Informe o valor da altura: ");
    scanf("%d", &altura);

    return 0;
}
[24/07, 18:51] Milaaa: 01.#include <stdio.h>
            
int main() {
 printf("Total      =        100%%\n");
 printf("IVA        =         17%%\n");
 printf("IRS        =         15%%\n");
 printf("-------------------------\n");
 printf("Liq.      =          68%%\n");
  return 0;
}
02.#include <stdio.h>

int main() {
    int num1, num2;

    
    printf("Informe o primeiro numero: ");
    scanf("%d", &num1);

    printf("Informe o segundo numero: ");
    scanf("%d", &num2);

    printf ("*-significa multiplicação, ele multiplica valores\n");
    printf("%%-significa resto da divisão, ele ajuda a saber se um numero é multiplo de outro, além de da o resto da divisão");

    
    printf("\nNumero 1 | Numero 2 | Operacao | Resultado\n");
    printf("-------------------------------------------\n");

    
    printf("%d        | %d        | %d + %d = | %d\n", num1, num2, num1, num2, num1 + num2);
    printf("%d        | %d        | %d - %d = | %d\n", num1, num2, num1, num2, num1 - num2);
    printf("%d        | %d        | %d * %d = | %d\n", num1, num2, num1, num2, num1 * num2);
    printf("%d        | %d        | %d / %d = | %d\n", num1, num2, num1, num2, num1 / num2);
    printf("%d        | %d        | %d %% %d = | %d\n", num1, num2, num1, num2, num1 % num2);

    return 0;
}
03.#include <stdio.h>
            
int main() {
  int num1;

  printf("Informe um numero: ");
  scanf("%d", &num1);

  if (num1 % 2 == 0){
    printf("O numero é par");
  } else
  {
    printf("O numero é impar");
  }

  return 0;
}
04.#include <stdio.h>

int main() {
    int num1, num2;
    printf("Digite o primeiro número inteiro: ");
    scanf("%d", &num1);

    printf("Digite o segundo número inteiro: ");
    scanf("%d", &num2);

    
    if (num2 != 0) {
        if (num1 % num2 == 0) {
            printf("%d é múltiplo de %d.\n", num1, num2);
        } else {
            printf("%d não é múltiplo de %d.\n", num1, num2);
        }
    }else {
       printf("Não é possível dividir por zero!\n");
   }

    return 0;
}
