# g
#include<stdio.h>
#include<conio.h>
main()
{
int a,b,c,d,sum;
printf("enter the values");
scanf("%d%d",&a&b);
c=&a;
d=&b;
sum=(*c)+(*d);
printf("sum is:%d",sum);
}
