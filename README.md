# Factorial-finding-in-C
In this repository, program for finding factorial of a number is done in 
C
#include<stdio.h> 

int main() 

{ 

int num; 

printf("Enter you number"); 

scanf("%d",&num); 

int ans = fact(num); 

printf("Factorial of %d is %d",num,ans); 

} 

int fact(int num) 

{ 

int ans; 

if(num==1) 

return 1; 

ans = num * fact(num-1); 

return ans; 

}
