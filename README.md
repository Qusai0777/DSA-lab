# DSA-lab
all c practice program in c (DSA) lab



== make a progam in c for factorial using recursion ==
code==

#include <stdio.h>

int main () {

int num,i,fact = 1;

printf("Enter a number: "); 

scanf("%d",&num);
if (num<0){
    printf("\nFactorial of negative numbers does not exist.\n");
}
else{
    for(i=1;i<=num;i++)
{
    //The *= operator first multiplies the value of the expression (on the right-hand side of the operator) by the value of the variable or property (on the left-hand side of the operator). 
    fact *= i;
}
printf("%d",fact);
    
}
    return 0;
}
