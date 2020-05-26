#include<stdio.h>
#define PI 3.14159
int main()
{ 
 int radius;
 printf("Enter radius:");
 scanf("%d",&radius);
 printf("volume is : %f \n\n", (float)4 *(radius*radius*radius)/3 );
 return 0;
}