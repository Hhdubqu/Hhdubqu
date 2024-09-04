#include<stdio.h>

int main()
{
	int a,b;
	int sum,rest,mult,div;
	
	printf("ingrese el primer valor (entero): \n");
	scanf("%d",&a);
	
	printf("ingrese el segundo valor (entero): \n");
	scanf("%d",&b);
	
	sum= a+b;
	rest= a-b;
	mult= a*b;
	div= a/b;
	
	printf("el resultado de la suma es: %d \n",sum);
	printf("el resultado de la resta es: %d \n",rest);
	printf("el resultado de la multiplicacion es: %d \n",mult);
	printf("el resultado de la division es: %d \n",div);
	
	
	return 0;
}

#include<stdio.h>

int main()
{
	float a,b;
	float sum,rest,mult;
	float div;
	
	printf("ingrese el primer valor (entero): \n");
	scanf("%f",&a);
	
	printf("ingrese el segundo valor (entero): \n");
	scanf("%f",&b);
	
	sum= a+b;
	rest= a-b;
	mult= a*b;
	
	printf("el resultado de la suma es: %.0f \n",sum);
	printf("el resultado de la resta es: %.0f \n",rest);
	printf("el resultado de la multiplicacion es: %.0f \n",mult);
	
	div= a/b;
	
	if(div == 0)
	{
		printf("error en la division");
	}
	else
	{
		printf("el resultado de la division es: %.2f \n",div);
	}
