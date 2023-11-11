# EX-01-2c

## AIM
To write a C program to find a maximum of two integers using a conditional operator.
## ALGORITHM
1. Start the program.
2. Read two variables.
3. Find maximum of two number using conditional operator (?:).
4. Display the result.
5. Stop the program.
## PROGRAM
```
#include <stdio.h>
int main()
{
int num1, num2, max;
scanf("%d%d", &num1, &num2);
max = (num1 > num2) ? num1 : num2;
printf("Maximum between %d and %d is %d", num1, num2, max);
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/c6f11af2-15e7-4409-809c-d2c4ad3f870e)

## RESULT
Thus the program  has been executed successfully.
