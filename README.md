#include<stdio.h>
#include<stdlib.h>
int main()
{
int a;
printf("enter your marks");
scanf("%d",&a);
if(a>=85 && a<100)
{
	printf("**** GRADE A ****");
}
else if(a>=70 && a<84)
{
	printf("****GRADE B****");
}
else if(a>=55 && a<69)
{
	printf("****GRADE C****");
}
else if(a>40 && a<54)
{
printf("****GRADE D****")	
}
else if(a<40)
{
	printf("**** GRADE F****");
}
return 0;
}
