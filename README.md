## EX.NO:1B
##  C program to print the the sum of its digits of a given a five digit integer n
## Date:
## AIM:
To write a C program to print the the sum of its digits of a given a five digit integer n
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
![image](https://github.com/Yogabharathi3/1/assets/118899387/a391c28b-2f13-4b4c-b3d7-be2c3ab031c9)

## Result:
Thus, the program is successfully verified.
