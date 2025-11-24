# c-2
find the avearge and sum of  a number   


#include<stdio.h>
#include<conio.h>
int main ()
{
    int a,b,c,sum;
    float d ;
    printf("enter three values");
    scanf("%d %d %d", &a, &b, &c);
    sum = a+b+c;
    d = (a+b+c)/3;
    printf("\n sum is : %d\n" , sum);
    printf("\n avg is : %f \n",d );
    return 0;
}
