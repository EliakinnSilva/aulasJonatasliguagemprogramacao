# aulasJonatasliguagemprogramacao
#include <string.h>
#include <stdio.h>
int main(){
    struct aluno{
        int matricula;
        char nome[80]; 
        
    };
        typedef struct aluno lista;
        lista si[30];
        si[0].matricula=202201;
        strcpy(si[0].nome,"maria silva");

    return 0;
}
======================================================
#include <stdio.h>
int soma(int n1,int n2);
void main(){
    int a=soma(10,15);
    printf("a=%d",a);
}
int soma(int n1, int n2){
    int n3=n1+n2;
    printf("n3=%i\n",n3);
return n3;
}
======================================================
#include <stdio.h>
int main()
{
    int x=10;
    int*ponteiro;
    ponteiro=&x;
    int y=20;
    *ponteiro=y;
    printf("x:%i\ny:%i",x,y);
    getchar();
    return 0;
}
==================================================

#include <stdio.h>

int main()
{
    int x=10;
    int*ponteiro;
    ponteiro=&x;
    printf ("Valor de x: %i\n",x);
    printf("end. de x:%i\n",&x);
    printf("&ponteiro: %i\n",&ponteiro);
    printf("ponteiro:%i\n",ponteiro);
    printf("*ponteiro:%i\n",*ponteiro);
    getchar();

    return 0;
}
==========================================================
