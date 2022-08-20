# assign-arithmaetic
This is a program for evaluation of an expression with compound assignment operator and arithmetic operator. as priority of arithmetic operator is greater than assignment it gives a contrast result .
#include<stdio.h>
#include<conio.h>
void main()
{
	int a,b,c;
	printf("Enter one number a:");
	scanf("%d",&a);
	printf("Enter second number b:");
	scanf("%d",&b);
	printf("Enter third number c:");
	scanf("%d",&c);
	a*=b+c;
	printf("Value of a is %d",a);
}



Output:
Enter one number a:5
Enter second number b:7
Enter third number c:2
Value of a is 45
