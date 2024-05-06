## EX.NO:2D
##  C program to print the sum of the integers in the array
## Date:
## AIM:
To Write a C program  to print the sum of the integers in the array
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Calculate sum of integers in the array
### STEP 4:
Print the output
## Program:
```
#include<stdio.h> 
#include <stdlib.h>
int main()
{ int limit,i,sum=0; 
int* ptr; 
scanf("%d", 
&limit);
ptr = (int*)malloc(limit * 
sizeof(int)); for (i = 0; i < limit; i++) 
{ scanf("%d", (ptr + i));
sum += *(ptr + i);
}
printf("%d",su
m); free(ptr); }

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/ff654196-6344-4529-b326-bd86720983a6)
## Result:
Thus, the program is successfully verified.
