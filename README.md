## EX.NO:6C
##  C program to delete elements in queue using Linked list
## Date:
## AIM:
To Write a C program to delete elements in queue using Linked list
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display delete elements in queue using linked list
### STEP 4:
Print the output
## Program:
``` 
void dequeue()
{
if(front == NULL)
{
printf("Queue is Empty!!!\n");
}
else{
struct Node *temp; 
temp=front; front=temp->next;
free(temp);
}
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/616c34e4-d7a9-4d9a-823a-3fd73a6b5e2d)

## Result:
Thus, the program is successfully verified.
