# EX-02-1b
## AIM
To write a C program to print the given triangular number pattern using loop.
## ALGORITHM
1. Start the program.
2. Read a variable.
3. Using two for loops print triangle number pattern.
4. Stop the program.
## PROGRAM
```
#include<stdio.h>
int main()
{
int n,i;
scanf("%d",&n);
for(i=n;i>=1;i--)
{
for(int j=i;j>=1;j--)
printf("%d",i);
printf("\n");
}
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/3597b816-ed6d-46a1-82f7-fbb488b97a82)

## RESULT
Thus the program  has been executed successfully.
