## EX.NO:2B
##  C program to print a five digit integer n, print the sum of its digits
## Date:
## AIM:
To Write a C program  to print a five digit integer n, print the sum of its digits
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Calculate sum of digits 
### STEP 4:
Print the output
## Program:
```
#include<stdio.h>
int main()
{
int a,rem,sum=0; 
scanf("%d",&a);
while(a>0)
{
rem=a%10; 
sum+=rem;
a/=10;
}
printf("%d",sum);
return 0;
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/619b8e28-262b-4226-a6e3-1ed45f0e335e)

## Result:
Thus, the program is successfully verified.
