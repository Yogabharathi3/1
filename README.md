## EX.NO:1C
##  C program to create a file with name "Staff.txt"
## Date:
## AIM:
To Write a C program to create a file with name "Staff.txt"
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Create the file
### STEP 4:
Print the output
## Program:
```
: #include 
<stdio.h> int main() 
{FILE *fp; 
fp=fopen("Staff.txt","
w"); if(fp!=NULL)
{printf("File Created Successfully\n");
}
printf("File Opened\n"); 
fclose(fp);
printf("File Closed\n");
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/c9abf6de-704d-4f8a-a6bc-df466fc192fb)

## Result:
Thus, the program is successfully verified.
