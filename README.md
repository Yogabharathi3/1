## EX.NO:5B
##  C program to print the 10th term of the series
## Date:
## AIM:
To Write a C program to print the 10th term of the series
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Calculate the 10th term of serious 
### STEP 4:
Print the output
## Program:
``` 
#include 
<stdio.h>
int find_nth_term(int n, int a, int b, int c) {
if(n==1) 
return a; 
else 
if(n==2) 
return b; 
else 
if(n==3) 
return c;
else
return find_nth_term(n-1,b,c,a+b+c);
}
int main() {
int n, a, b, c;
scanf("%d %d %d %d", &n, &a, &b, &c); 
int ans = find_nth_term(n, a, b, c); 
printf("%d", ans);
return 0;
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/76dc8b29-dc9d-461d-9e2e-29205be3f4d1)

## Result:
Thus, the program is successfully verified.
