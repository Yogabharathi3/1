# EX-03-1b
## AIM
Create a C program to check whether the given number is Armstrong number or not.
## ALGORITHM
1. Define the function
2. Call the function
3. Check Armstrong Condition
4. End the program
## PROGRAM
```
#include <stdio.h>
int main(){
int n,a=0,b=0,temp=0;
scanf("%d",&n);
temp=n;
while(n!=0)
{b=n%10;
a=a+(b*b*b);
n=n/10;
}
if(temp==0)
printf("%d is armstrong number",temp);
else
printf("%d is not a armstrong number",temp);
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/5a7f9731-3436-4674-a387-40b50bf4d3a4)

## RESULT
Thus the program  has been executed successfully.
