# -
#include <stdio.h> 
#include <stdlib.h>   
int main() 
{
    float a,b,c;
    scanf("%f",&amp;a);
    scanf("%f",&amp;b);
    scanf("%f",&amp;c);
    b = b/1200 + 1;
    a  = a*b-c;
    printf("Balance remaining after first payment: $%.2f\n",a);
    a  = a*b-c;
    printf("Balance remaining after second payment: $%.2f\n",a);
    a  = a*b-c;
    printf("Balance remaining after third payment: $%.2f\n",a);
    return 0;
}
