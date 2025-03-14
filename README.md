# c-30
To check max of 2 num using a function and ternary operators,using return values while passing Arguments and by using mirror values
#include<stdio.h>
int max(int a,int b)
{
    return (a>b)?a:b;
}
int main()
{
   int x,y;
   printf("enter the value of x");
   scanf("%d",&x);
   printf("enter the value of y");
   scanf("%d",&y);
   printf("maximum:%d \n",max(x,y));
    return 0;
}
