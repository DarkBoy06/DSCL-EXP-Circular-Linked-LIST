# DSCL-EXP-Circular-Linked-LIST
Description: This C program creates a linked list with three nodes, where each node contains an integer data and a pointer to the next node. The third node's next pointer points back to the first node, creating a circular linked list.

Algorithm:

Declare a struct node with two members, an integer data and a pointer to the next node. Dynamically allocate memory to create three nodes using the malloc() function. Set the data value of the first node to 20 and the next pointer to point to the second node. Set the data value of the second node to 30 and the next pointer to point to the third node. Set the data value of the third node to 40 and the next pointer to point back to the first node. Print the data, self-address, and next node address of each node using printf() function.

Output:

data=20 selfaddr=16575728 nextaddr=16575760 data=30 selfaddr=16575760 nextaddr=16575792 data=40 selfaddr=16575792 nextaddr=16575728
