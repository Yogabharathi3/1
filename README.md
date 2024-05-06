## EX.NO:4B
##  C program to insert a node in a linked list
## Date:
## AIM:
To Write a C program to insert a node in a linked list
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display the insert using linked list
### STEP 4:
Print the output
## Program:
```
struct Node{ char 
data; struct 
Node *next;
}*head;
void insert(char data)
{ struct Node *n=(struct Node*)malloc(sizeof(struct 
Node)); struct Node *temp; temp=head;
if(head==NULL)
{ head = n;
head->data = data; n-
>next=NULL;
return;
}
while(temp->next!=NULL) 
{temp=temp->next;} n-
>data=data; n->next=NULL;
temp->next= n;
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/d0137da1-40e7-449d-8477-b03831bcfbeb)
## Result:
Thus, the program is successfully verified.
