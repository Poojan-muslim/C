# calculator in c

#include <stdio.h>

int main (){
	//Setuping up
	int firstnumber , secondnumber;
	int add, sub, mul, div;
	
	//iNPUT AND PRINT 
	printf("Enter first number\n");
	scanf("%d",&firstnumber);
	printf("Enter second number\n");
	scanf("%d",&secondnumber);
	
	//Calculations
	add = firstnumber + secondnumber;
	sub = firstnumber - secondnumber;
	mul = firstnumber * secondnumber;
	div = firstnumber / secondnumber;
	
	//Printing final answers
	printf("This is sum %d\n", add);
	printf("This is subtract %d\n", sub);
	printf("This is multiplaction %d\n", mul);
	printf("This is devide %d\n", div);
	
	return 0;
	
	
}
