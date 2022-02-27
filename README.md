# EXCHANGE-OF-NUMBER-BY-USING-THIRD-VARIABLE

#include<stdio.h>
#include<conio.h>

void main()
{
int a, b, temp;
printf("ENTER THE NUMBER");
scanf("%d%d", &a,&b);
a=b;
b=temp;
temp=a;
printf("%d%d", &a,&b);
}
