// # hello-world
Just another repository
By this I want to start using Github "to making code in C and C++
That's the end.
/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>
#include <stdlib.h>
//code c pour le calcul de la somme de deux nombre entier

int main(void)
{
    int a, b, s;
    printf("entrer la valeur de a et b\n");
    scanf("%d", &a); scanf("%d", &b);
    s=a+b;
    printf("s = %d\n", s);
    return 0;
}
// A jout des 4 autres opérations majeurs en mathématiques
#include <stdio.h>
#include <stdlib.h>
//code c pour le calcul de la somme de deux nombre entier

int main(void)
{
    int a, b, somme, Multi, soustra, division;
    printf("entrer la valeur de a et b\n");
    scanf("%d", &a); scanf("%d", &b);
    somme=a+b; Multi=a*b; soustra= a-b; division=a/b;
    printf("somme = %d\n,Multi = %d\n, soustra = %d\n, division= %d\n", somme, Multi, soustra, division);
    return 0;
}
