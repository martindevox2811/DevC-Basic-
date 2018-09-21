# DevC-Basic-
DevC 
#include <stdio.h>
#include <math.h>
int main (){
	float a, b, c, delta;
	printf ( " Nhap a#0, b, c:");
	scanf ( "%f%f%f", &a, &b, &c);
	
	if (a==0){
		printf (" Nhap lai a#0: ");
		scanf ( "%f", &a);
		
	}
	if (a==0){
		printf (" Nhap lai a#0: ");
		scanf ( "%f", &a);
	}
	
	delta = b*b - 4*a*c;
	
	if ( delta < 0) printf (" Phuong trinh vo nghiem");
		else if ( delta == 0) printf (" Phuong trinh co nghiem kep x = %f", -b/(2*a) );
				else printf (" Phuong trinh co nghiem x1 =  %f\nx2 = %f",
				((-b-sqrt(delta))/(2*a)), (-b+sqrt(delta))/(2*a));
	return 0;
}
