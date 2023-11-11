# EX-01-2a
## AIM
To write a C program to check whether the given number is even number and if it is even check whether the given number it is less than or equal to 10 or not using nested if.
## ALGORITHM
1. Start the program.
2. Read one variable.
3. Check whether the given number is odd or even using if and else.
4. Display the result.
5. Stop the program.
## PROGRAM
#include <stdio.h>
int main()
{
int num;
scanf("%d",&num);
if(num%2==0)
{
printf("The number is even \n");
if(num<=10)
{
printf("The number is less than or equal to 10");
}
else
{
printf("The number is not less than or equal to 10");
}
}
else
printf("The number is NOT an even number");
}
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/acc9e010-acd6-47e1-a5cc-553a0ffefa13)
## RESULT
Thus the program  has been executed successfully.
