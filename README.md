## EX.NO:1B
##  C program to print ten space-separated integers in a single line denoting the frequency of each digit from 0 to 9
## Date:
## AIM:
To Write a C program to Print ten space-separated integers in a single line denoting the frequency of each digit from 0 to 9 .
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Calculate the frequency of each digit from 0 to 9
### STEP 4:
Print the output
## Program:
```
#include<stdio.h> 
#include<string.h> 
int main()
{char num[20]; 
scanf("%s",num);
int count[20];
char digit[]={'0','1','2','3','4','5','6','7','8','9'};
for(int i=0;i<10;i++)
{count[i]=0; for(int 
j=0;j<strlen(num);j++)
{ if(digit[i]==num[j])
count[i]++;
}
printf("%d ",count[i]);
}
return 0;
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/3209016f-f73a-4558-8683-c16cf04430fb)

## Result:
Thus, the program is successfully verified.
