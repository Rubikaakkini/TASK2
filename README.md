# TASK2
COMPANY CODETECH IT SOLUTIONS NAME : Rubika A
INTERN ID : CT08HCQ 
**DOMAIN NAME ** : C Programming
**BATCH DURATION **: December 30th, 2024 to January 30th, 2025
MENTOR NAME : Neela Santhosh Kumar

THE DESCRIPTION OF THE TASK

This program is a Singly Linked List implementation in C, showcasing fundamental operations like Insertion, Deletion, and Traversal. It uses a dynamic data structure where each element (node) points to the next one, forming a chain.

Here is a breakdown of the program and its key components:

1. Data Structure
The program defines a Node structure:
c
Copy
Edit
struct Node {
    int data;
    struct Node* next;
};
data: Holds the integer value of the node.
next: A pointer to the next node in the list.
2. Core Operations
a. Insert at Beginning
Inserts a new node containing user-provided data at the start of the list.
The new node becomes the head of the list.
Function:
c
Copy
Edit
void insertAtBeginning(struct Node** head, int data)
Example:
plaintext
Copy
Edit
Before: NULL
After inserting 10: 10 -> NULL
b. Insert at End
Inserts a new node at the tail of the list. If the list is empty, the new node becomes the head.
Traverses the list to find the last node and appends the new node.
Function:
c
Copy
Edit
void insertAtEnd(struct Node** head, int data)
Example:
plaintext
Copy
Edit
Before: 10 -> NULL
After inserting 20: 10 -> 20 -> NULL
c. Delete a Node
Removes the first occurrence of a node with the specified value.
Updates the links to preserve the integrity of the list.
If the node does not exist, a message is displayed.
Function:
c
Copy
Edit
void deleteNode(struct Node** head, int key)
Example:
plaintext
Copy
Edit
Before: 10 -> 20 -> NULL
Deleting 10
After: 20 -> NULL
d. Traverse the List
Traverses the entire list, starting from the head, and displays the data of each node.
If the list is empty, a message is displayed.
Function:
c
Copy
Edit
void traverseList(struct Node* head)
Example:
plaintext
Copy
Edit
Linked List: 10 -> 20 -> NULL
3. Interactive Menu
The program offers a menu-driven interface to perform operations dynamically:
Option 1: Insert at the beginning.
Option 2: Insert at the end.
Option 3: Delete a node by value.
Option 4: Traverse and display the list.
Option 5: Exit the program.
The menu runs in a loop until the user chooses to exit.
4. Use Cases
Dynamic Memory Allocation: Uses malloc to allocate memory for nodes at runtime.
Practical Applications:
Storing and managing dynamic datasets.
Used as a foundation for advanced data structures like stacks, queues, and graphs.


** OUTPUT OF THE TASK

