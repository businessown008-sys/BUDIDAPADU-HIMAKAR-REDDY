#include<stdio.h>
int main()
{

float distance,mileage,fuel_price;
float fuel_required, total_cost;

printf("enter distance(km): ");
scanf("%f",&distance);

printf("enter vehicle mileage(km/1): ");
scanf("%f", &mileage);

printf("enter fuel price per litre:");
scanf("%f",&fuel_price);

fuel_required=distance/mileage;
total_cost=fuel_required*fuel_price;

printf("\nfuel required=%.2f litres",fuel_required);
printf("\ntotal fuel cost=rs. %.2f",total_cost);
}
