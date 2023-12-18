#include <stdio.h>

int main(){

int idade;    
int i;
    
for (i = 0; i < 2; i++){    
printf ("\ndigite sua idade:");
scanf ("%d",&idade);


if (idade >= 18){
    printf("\nmaior idade:%d", idade);
    
}
else {
    printf("\nmenor idade: %d", idade);
}

}
    return 0;
}
