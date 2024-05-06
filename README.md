## EX.NO:6D
##  C program to insert elements in queue using Linked list
## Date:
## AIM:
To Write a C program to insert elements in queue using Linked list
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display insert elements in queue using linked list
### STEP 4:
Print the output
## Program:
``` 
struct Node
{ float data; struct Node *next; 
}*front=NULL,*rear=NULL;
void enqueue(float data)
{
struct Node *p = (struct Node*)malloc(sizeof(struct Node));
p->data=data; p->next=NULL;
if(front==NULL)
{
front=rear=p;
} 
else
{
rear->next=p;
rear=p;}
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/616c34e4-d7a9-4d9a-823a-3fd73a6b5e2d)

## Result:
Thus, the program is successfully verified.
