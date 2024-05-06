## EX.NO:6B
##  C program to push an element in Stack using Linked List
## Date:
## AIM:
To Write a C program to push an element in Stack using Linked List
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display push stack using linked list
### STEP 4:
Print the output
## Program:
``` 
void push(char data)
{
struct Node *ptr=(struct Node*)malloc(sizeof(struct Node)); 
if(head==NULL)
{
ptr->data=data; ptr-
>next=NULL;
head=ptr;
} 
else
{
ptr->data=data; ptr->next=head;
head=ptr;
}
}
```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/ff1f4802-2e9c-4af7-bbb0-6d52ccc82a98)

## Result:
Thus, the program is successfully verified.
