## EX.NO:4D
##  C program to insert an element in double linked
## Date:
## AIM:
To Write a C program to insert an element in double linked
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display the insert of an element using double linked list
### STEP 4:
Print the output
## Program:
```
struct Node
{ struct Node *prev, 
*next; float data; 
}*head;
void insert(float data)
{ struct Node *ptr,*temp; ptr=(struct 
Node *)malloc(sizeof(struct Node)); 
if(ptr==NULL)
{ printf("OVERFLOW\n");}
else
{ ptr->data=data; 
if(head==NULL)
{ ptr->next=NULL; ptr-
>prev=NULL;
head=ptr; }
else
{ temp=head; 
while(temp-
>next!=NULL) 
{temp=temp->next; } 
temp->next=ptr; ptr-
>prev=temp; ptr-
>next=NULL;}
} }

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/af8911cd-4b4a-46c3-beb8-400fc4b290af)

## Result:
Thus, the program is successfully verified.
