# Rt-angled-Triangle
Created by Abdulrahim Mulla


//Rt-angle Triangle
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int i,j,r;
	
	printf("Enter the Number of Rows : \n");
	scanf("%d",&r);
	
	printf("\n \t Printing 6 rows of '01' in Rt-angled Triangle \n");
	for(i=1; i<=r; i++)
	{
		for(j=1; j<=i; j++)
		{
		printf("01");
		}
	printf("\n");	
	}
	return 0;
}

