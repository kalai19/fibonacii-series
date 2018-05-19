# fibonacii-series
#include <stdio.h>
 
int main()
{
	int a=0,b=1,n,c;
	printf("\n enter the number");
	scanf("%d",&n);
	printf("\n fibonacci series are");
	printf("\n%d",a);
	printf("\n%d",b);
	while(n>2)
	{
		c=a+b;
		printf("\n%d",c);
		a=b;
		b=c;
		n--;
		}
		
	return 0;
}
 
