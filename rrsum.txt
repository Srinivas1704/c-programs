#include<stdio.h>
void main()
{
	int a[100][100];
	int i,j,r,c,rr,sum; 
	printf("Enter how many rows \n");
	scanf("%d",&r);
	printf("Enter how many cols \n");
	scanf("%d",&c);
	printf("Enter elements into array \n");
	for(i=1;i<=r;i++)
	{
		for(j=1;j<=c;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}
	
	printf("Enter the row number to display its sum:");
      scanf("%d",&rr);
	for(i=1;i<=r;i++)
	{
        if(rr==i)
        {
		sum=0;
		for(j=1;j<=c;j++)
		{
			sum=sum+a[i][j];
		}
        }		
	}
      printf(" %d Row sum= %d \n",rr,sum);
	
}
