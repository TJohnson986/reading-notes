## Linked List Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

## Linked Lists

A linked list is a sequence of nodes that are connected, more specifically is that each node references the next node in the link.

Two types of linked lists: singly and doubly. Singly means that there is only one reference per node, and that reference is to the next node. Doubly linked lists have two references per node, one that references the previous node and one that references the next node.

The head is a reference of the first node in a linked list. The current is the node currently being looked at.

#### Traversal

Best way to traverse a linked list is through the use of a while loop and the use of the Next value in each node.

A variable called current is created and first assigned to the head as the beginning of the list. The logic of the while loop typically is that if current does not equal null, move to the next node.
