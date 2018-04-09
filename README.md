# helloWorld
第一天
a,b中取最大值，使用的c编写
#include<stdio.h>
int max(int x,int y)
{
	int z;
	if(x>y)
		z=x;
	else
		z=y;
	return z;
}
void main(void)
{
	int a,b,c;
	printf("a,b=");
	scanf("%d%d",&a,&b);
	c=max(a,b);
	printf("max=%d\n",c);
}
