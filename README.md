# MeP2.D1
Dit is opdracht voor versiebeheer
Iedereen voegt een command toe met zijn naam
// Laura Bornhijm
// Kaj van Beest
//Mike van Jaarsveld (Balotelli9)

#include <stdio.h>
#include <stdlib.h>

int main()
{
    printf("Wat is R1? ");
    int R1;
    scanf("%d", &R1);
    printf("Wat is R2? ");
    int R2;
    scanf("%d", &R2);
    int Rv = R1 + R2;
    printf("De Rv is %d + %d = %d.", R1, R2, Rv);
    return 0;
}
