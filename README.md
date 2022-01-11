# factorial-of-a-number-using-C
this c codes demonstrates how to find factorial of a number using for loop
#include <stdio.h>

int main()
{
    int n;
  printf("enter the no");
  scanf("%d",&n);
 int mul=1,i;
    for(i=1;i<=n;i++)
    {
        mul=mul*i;
    }
printf("the factorial is %d", mul);
return 0;
