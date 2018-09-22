#include <stdio.h>
main()
{
	float High1 ;
	float Base1 ;
	float Answer1 ;
	
	printf("Triangle Area Calculator");
	printf("\nEnter High : ");
	scanf("%f",&High1);
	
	printf("\nEnter Base : ");
	scanf("%f",&Base1);
	
	Answer1=0.5*Base1*High1;
	printf("\nArea of Triangle : %.2f",Answer1);
	printf("\n---------------------------------");
	
	
	
	float Radius2 ;
	float PI2=3.14;
	float Answer2;
	
	printf("\nCircle Area Calculator");
	printf("\nEnter Radius : ");
	scanf("%f",&Radius2);
	
	Answer2=PI2*(Radius2*Radius2);
	printf("\nArea of Circle : %.2f",Answer2);
	printf("\n---------------------------------");

	float side3 ;
	float Answer3 ;
	
	printf("\nSquare Area Calculator");
	printf("\nEnter Square : ");
	scanf("%f",&side3);
	
	Answer3=side3*side3;
	printf("\nArea of Square : %.2f",Answer3);
	printf("\n---------------------------------");
	
	return 0;
	
}
