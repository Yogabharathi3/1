## EX.NO:6A
##  C program to display stack elements using Linked List(store float data in stack )
## Date:
## AIM:
To Write a C program to display stack elements using Linked List(store float data in stack )
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display stack using linked list
### STEP 4:
Print the output
## Program:
``` 
struct Node
{ float data; 
struct Node 
*next;
}*head; 
void 
display()
{
struct Node *p; 
p=head;
while(p!=NULL)
{ printf("%.2f\n",p->data);
p=p->next;
}
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/f590d282-1c3a-4c78-a879-748684c67ce2)

## Result:
Thus, the program is successfully verified.
