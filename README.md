

#include<stdio.h>
#define PI 3.14;

float calculate_area(float);
float circum_area(float );
int main()
{
float area, radius,circum;
printf("enter the circle radius:");
scanf("%f",&r);
printf("the area of the circle is %f",calculate_area(radius);
printf("the circumference of the circle is %f",circum_area(radius);
}

float calculate_area(float radius)
{
    return (PI * radius )* radius;
}
float circum_area(float radius)
{
    return 2*(PI*radius);
    }
