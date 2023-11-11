# EX-02-1d
## AIM
To write a c program to find the sum of even digits using for loop.
## ALGORITHM
1. Start the program.
2. Read a variable.
3. Using for loop print the sum of even digits.
4. Stop the program.
## PROGRAM
```
#include<stdio.h>
int main()
{
int a,i,s=0;
scanf("%d",&a);
for(i=1;i<=a;i++)
{
if(i%2==0)
{
s+= i;
printf("%d ",i);
}
}
printf("\n%d ",s);
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/e39bbce9-b362-4136-9f31-9f3df5a334a8)

## RESULT
Thus the program  has been executed successfully.
