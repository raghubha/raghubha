- š Hi, Iām @raghubha
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
raghubha/raghubha git hub
--->
include <stdio.h> 
#include <conio.h> 
#include <math.h> 
void main() 
{ 
	int p,t; 
	float r,amt,ci; 
	clrscr(); 

	printf ("Enter Principal Amount: "); 
	scanf ("%d",&p); 

	printf ("Enter Time: "); 
	scanf ("%d",&t); 

	printf ("Enter Rate of interest: "); 
	scanf ("%f",&r); 

	amt= p*pow((1+r/100),t); 
	ci = amt-p; 

	printf ("Simple interest: %7.2f ",ci); 
	printf ("Total amount: %7.2f ",amt); 

	getch(); 

}
