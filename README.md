/******************************************************************************

FATORIAL EM FOR! - EM LINGUAGEM C

*******************************************************************************/
    
    #include <stdio.h>

    int main(){
    
    int num, i, contador = 1;
    
    printf("Veja o fatorial de número!\n");
    printf("Digite um número: ");
    scanf("%d", &num);
    
    printf("%d! = ", num);
    
    for(i = num; i > 0; i--){
        
        printf("%d", i);
        printf(" * ");
        
        contador = contador * i;
    }
    
    printf("= %d", contador);
    
    return 0;
    }
