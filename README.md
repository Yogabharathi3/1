# EX-03-1c
## AIM
Create a C program to read n elements as input and print the first three elements of an array
## ALGORITHM
1. Define the array
2. Read the input
3. Print the first three elements
4. End the program
## PROGRAM
```
#include<stdio.h>
int main(){
int i,n,a[5];
scanf("%d",&n);
for(i=0;i<n;i++) {
scanf("%d",&a[i]);
}
for(i=0;i<n;i++)
{ printf("%d
",a[i]);
}
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/5e33e195-7539-4fa9-86f8-2fbb7e82d28d)

## RESULT
Thus the program  has been executed successfully.
