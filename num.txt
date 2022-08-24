#include<stdio.h>
void main()
{
 int i,j,num,n;
 scanf("%d",&n);
 for(i=1;i<=n;i++)
 {
  num=n;
  for(j=1;j<=i;j++)
  {
    printf("%d ",num);
    num--;
  }
  printf("\n");
 }
}