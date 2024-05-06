## EX.NO:5D
##  C program to Find the Percentage or marks of students
## Date:
## AIM:
To Write a C program to Find the Percentage or marks of students
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Calculate the percentage or marks of students
### STEP 4:
Print the output
## Program:
``` 
#include<stdio.h> 
int main()
{ int sum=0,per; 
int m1,m2,m3;
scanf("%d %d 
%d",&m1,&m2,&m3); 
sum=m1+m2+m3; per=sum/3; 
if(per>=60&&per<=100)
printf("You are 1st");
else if(per>=50&&per<=60) 
printf("You are 2nd");
else if(per>=40&&per<=50)
printf("You are 3rd"); 
else
printf("You are Fail");
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/5f6fbc58-e856-4bfe-8f18-c671e1309f72)

## Result:
Thus, the program is successfully verified.
