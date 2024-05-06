## EX.NO:4C
##  C program to traverse a double linked list
## Date:
## AIM:
To Write a C program to traverse a double linked list
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display the traverse using double linked list
### STEP 4:
Print the output
## Program:
```
struct Node
{
struct Node *prev; struct 
Node *next; float data; 
}*head;
void display()
{
struct Node *ptr; ptr=head; 
while(ptr!=NULL)
{ printf("%.2f\n",ptr->data); ptr=ptr-
>next;
}
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/657c493e-3aea-4225-8ea0-9ba7ed643dbf)

## Result:
Thus, the program is successfully verified.
