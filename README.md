# EX-03-1a
## AIM
Write a program to prepare EMI calculation for 2000000 ,8.24,6Years using function withreturn type without arguments.
## ALGORITHM
1. Define the function
2. Call the function
3. Print the EMI amount
4. Handle errors
5. End the program
## PROGRAM
```
#include<stdio.h>
#include<math.h>
float emi(float x,float y,float
z){y=y/(12*100);
z=z*12;
float isl=x * y *pow((1+y),z) / (pow(1+y,z)-1);
return isl;
}
int main(){
float a=2000000,b=8.24,c=6,emos;
scanf("%f%f%f",&a,&b,&c);
emos=emi(a,b,c);
printf("Monthly EMI is= %.3f",emos);
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/1/assets/118899387/02ecfaf3-93a2-4415-9458-84865a453995)

## RESULT
Thus the program  has been executed successfully.
