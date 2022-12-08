---
# Data Structures and Algorithm Cheat Sheet

### This is a simple Data Structure and Algorithm cheat sheet for biginners

#### Here we only focus on the worst time complexity
---

## Data Structures

> **ARRAYS**

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Insert    | O(n)            |
| Search    | O(n)            |
| Delete    | O(n)            |

> **HASH MAPS**

Maps, dictionaries, and associative arrays all describe the same abstract data type. But hash map implementations are distinct from treemap implementations in that one uses a hash table and one uses a binary search tree.
There are at least two ways to implement hashmap:

1. Array: Using a hash function to map a key to the array index value. Worst Case: O(n), Average Case: O(1).
2. Binary Search Tree: using a self-balancing binary search tree to look up for values. Worst Case: O(log n), Average Case: O(log n).

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Insert    | O(1)            |
| Search    | O(1)            |
| Delete    | O(1)            |

> **LINKED LIST**

 A linked list is the most sought-after data structure when it comes to handling dynamic data elements. A linked list consists of a data element known as a node and each node consists of two fields: one field has data, and in the second field, the node has an address that keeps a reference to the next node.

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(n)            |
| Insert    | O(n)            |
| Search    | O(n)            |
| Delete    | O(n)            |

> **STACKS**

A stack is a linear data structure in which insertion and deletion of elements are done at only one end, which is known as the top of the stack. Stack is called a last-in, first-out (LIFO) structure because the last element which is added to the stack is the first element which is deleted from the stack. Stacks are implemented using arrays and linked lists.

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(n)            |
| Insert    | O(1)            |
| Search    | O(n)            |
| Delete    | O(1)            |

> **QUEUES**
 
A queue is defined as a linear data structure that is open at both ends and the operations are performed in First In First Out (FIFO) order
structure in which the element that is 
inserted first is the first one to be taken out. 

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Insert    | O(1)            |
| Search    | O(n)            |
| Delete    | O(1)            |

> **TREES**

> **GRAPHS**

 
Unlike other common data structures, a graph consist of vertices (V) and edges (E).
Thus:

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(V + E)        |
| Insert    | O(1)            |
| Search    | O(V + E)        |
| Delete    | O(E)            |
---

## Algorithms

| Algorithm | Time Complexity |
| --------- | --------------- |
