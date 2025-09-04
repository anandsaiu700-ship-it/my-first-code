#include<stdio.h>
int main(){
	int televisions,cost_of_televisions,bill,discount;
	printf("enter the no of televisions=");
	scanf("%d",&televisions);
	printf("enter the cost of each television=");
	scanf("%d",&cost_of_televisions);
	bill=televisions*cost_of_televisions;
	if (televisions>2)
	{
		discount=bill-5000;
		printf("after discount your bill = %d/-",discount);
	}
	else
	printf("your bill = %d/-",bill);
	
	
	return 0;
}


