# COLLEGE-FEE-DETAIILS
#include <stdio.h>

int main()
{
int clgfee,years,busfee,bookfee,totalfee;
printf("ENTER YOUR COLLEGE FEE: ");
scanf("%d", &clgfee);
printf("ENTER HOW MANY YEARS YOU HAVE STUDIED: ");
scanf("%d", &years);
printf("ENTER YOUR BUYS FEE: ");
scanf("%d", &busfee);
printf("ENTER YOUR Book FEE: ");
scanf("%d", &bookfee);
totalfee=(clgfee*years)+(busfee*years)+(bookfee*years);
printf("%d",totalfee);
return 0;
}
