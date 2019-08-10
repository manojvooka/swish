# swish
#include<stdio.h>
#include<math.h>
int main()
{
 int X,p,sum=0;
 scanf("%lld%lld",&X,&p);
 if((X>=0&&X<=10000)&&(p>=1&&p<=100))
  {
    while(x>=1)
    {
      sum=sum+x;
      X=(X-(X*p)/100);
    }
  printf("The amount to be collected is %lld");
  }
 else
  {
   printf("invalid");
  } 
return 0;
}
