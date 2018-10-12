#include<stdio.h>
void sum(int x,int y)
{
    int sum=0;
    sum=x+y;
    printf("The sum is: %d",sum);
}
int main()
{
    int a,b;
    printf("Enter the first number:");
    scanf("%d",&a);
    printf("Enter the second number:");
    scanf("%d",&b);
    sum(a,b); //'a' and 'b' passed as arguements
return 0;
}

