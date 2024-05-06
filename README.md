## EX.NO:1A
##  C program to check eligibility of the person to vote in election
## Date:
## AIM:
To write a C program for structure to check eligibility of the 
person to vote in election.
## Algorithm:
### STEP 1:
Define the Structure
### STEP 2:
Input Data
### STEP 3:
Check Eligibility
### STEP 4:
Get the output
## Program:
```
#include<stdio.h>
struct elig
{
int age;
char name[10];
};
int main()
{ struct elig e;
scanf("%d\n%s",&e.age,e.name); 
printf("Age:%d\nName:%s\n",e.age,e.name);
if(e.age>18) 
printf("eligibility:yes"); 
else printf("eligibility:no"); 
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/68645458-af3b-4bd9-a1f2-f385557288cd)

## Result:
Thus, the program is successfully verified
