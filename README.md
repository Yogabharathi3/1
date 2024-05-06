## EX.NO:2A
##  C program to print Hello Saveetha! on a single line, and then print the already provided input string to stdout
## Date:
## AIM:
To Write a C program print Hello Saveetha! on a single line, and then print the already provided input string to stdout
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Print hello saveetha 
### STEP 4:
Print the output
## Program:
```
#include<stdio.h> 
int main()
{
char str[20]; 
scanf("%[^\n]%*c",str); 
printf("Hello, Saveetha!\n%s",str);
return 0;
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/619b8e28-262b-4226-a6e3-1ed45f0e335e)

## Result:
Thus, the program is successfully verified.
