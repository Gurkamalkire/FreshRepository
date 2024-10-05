# FreshRepository
This is my new Git repository
<br> 
I'm giving a calculator Program:-
<br>
#include <stdio.h>
#include <stdlib.h>
void add(int a,int b)
{
    int total=a+b;
    printf("sum is %d \n",total);
}
void sub(int x,int y)
{
    int min=x-y;
    printf("subtraction is %d \n",min);
}
void multi(int m,int n)
{
    int prod=m*n;
    printf("Multiplication is %d \n",prod);
}
void op(int r,int s)
{
    int from=r/s;
    printf(" division is %d \n",from);
}
void main()
{
  int s;
  printf("Enter any number : \n");
  scanf("%d",&s);
if(s == 1)
{
    int num1, num2;
    printf("\nEnter any two numbers : ");
    scanf("%d%d",&num1,&num2);
    add(num1,num2);
}
else if(s == 2)
{
    int num1, num2;
    printf("\nEnter any two numbers : ");
    scanf("%d%d",&num1,&num2);
    sub(num1,num2);
}
else if(s == 3)
{
    int num1, num2;
    printf("\nEnter any two numbers : ");
    scanf("%d%d",&num1,&num2);
    multi(num1,num2);
}
else if(s == 4)
{
    int num1, num2;
    printf("\nEnter any two numbers : ");
    scanf("%d%d",&num1,&num2);
    op(num1,num2);
}else
printf("INVALID NUMBER");
}

