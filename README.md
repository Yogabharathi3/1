# EX-03-1d
## AIM
Write a C program to delete last element in an array
## ALGORITHM
1. Define the array
2. Read the input
3. Delete the last element
4. Print the last elements
5. End the program
## PROGRAM
```
#include<stdio.h>
int main(){
int a,i;
scanf("%d",&a);
int b[a];
for(i=0;i<a;i++) {
scanf("%d",&b[i]);
}
for(i=0;i<a-1;i++)
{
printf("%d ",b[i]);
}
return 0;
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/02c851e4-2d9a-4b89-bf39-7059622a73c8)

## RESULT
Thus the program  has been executed successfully.
