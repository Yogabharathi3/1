## EX.NO:4A
##  C program to traverse the linked list and display it in the following format
## Date:
## AIM:
To Write a C program to traverse the linked list and display it in the following format
## Algorithm:
### STEP 1:
Initialize variables
### STEP 2:
Read input
### STEP 3:
Display the linked list
### STEP 4:
Print the output
## Program:
```
struct Node{ char 
data; struct 
Node *next;
}*head;
void display()
{
struct Node* temp; 
temp=head;
while(temp!=NULL)
{ printf("%c\n",temp-
>data);
temp=temp->next;}
}

```
## Output
![image](https://github.com/Yogabharathi3/1/assets/118899387/026fff51-782f-45be-ac8b-710058b26d38)

## Result:
Thus, the program is successfully verified.
