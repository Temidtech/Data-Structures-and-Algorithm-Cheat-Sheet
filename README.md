---
# Data Structures and Algorithm Cheat Sheet

### This is a simple Data Structure and Algorithm cheat sheet for biginners
---

## Data Structures

>  ## **ARRAYS**

An array is a data structure for storing more than one data item that has a similar data type. The items of an array are allocated at adjacent memory locations. These memory locations are called elements of that array. The total number of elements in an array is called length.
Arrays work on an index system starting from 0 to (n-1), where n is the size or Length of the array

| Operation | Average Time complexity | Worst Time complexity |
| --------- | --------------- | ------------ |
| Access    | O(1)            |  O(1)        |
| Insert    | O(n)            |  O(n)        |
| Search    | O(n)            |  O(n)        |
| Delete    | O(n)            |  O(n)        |
<br>
<br>

> ## **HASH MAPS**

Maps, dictionaries, and associative arrays all describe the same abstract data type. But hash map implementations are distinct from treemap implementations in that one uses a hash table and one uses a binary search tree.
There are at least two ways to implement hashmap:

1. Array: Using a hash function to map a key to the array index value. Worst Case: O(n), Average Case: O(1).
2. Binary Search Tree: using a self-balancing binary search tree to look up for values. Worst Case: O(log n), Average Case: O(log n).

| Operation | Average Time complexity | Worst Time complexity |
| --------- | --------------- | -------- |
| Access    | O(1)            |  O(1)    |
| Insert    | O(1)            |  O(n)    |
| Search    | O(1)            |  O(n)    |
| Delete    | O(1)            |  O(n)    |
<br>
<br>

> ## **LINKED LIST**

 A linked list is the most sought-after data structure when it comes to handling dynamic data elements. A linked list consists of a data element known as a node and each node consists of two fields: one field has data, and in the second field, the node has an address that keeps a reference to the next node.

| Operation | Average Time complexity | Worst Time complexity |
| --------- | --------------- | --------|
| Access    | O(n)            |  O(n)   |
| Insert    | O(1)            |  O(1)   |
| Search    | O(n)            |  O(n)   |
| Delete    | O(1)            |  O(1)   |
<br>
<br>

> ## **STACKS**

A stack is a linear data structure in which insertion and deletion of elements are done at only one end, which is known as the top of the stack. Stack is called a last-in, first-out (LIFO) structure because the last element which is added to the stack is the first element which is deleted from the stack. Stacks are implemented using arrays and linked lists.

| Operation | Average Time complexity | Worst Time complexity |
| --------- | --------------- | ------- |
| Access    | O(n)            |  O(n)   |
| Insert    | O(1)            |  O(1)   |
| Search    | O(n)            |  O(n)   |
| Delete    | O(1)            |  O(1)   |
<br>
<br>

> ## **QUEUES**
 
A queue is defined as a linear data structure that is open at both ends and the operations are performed in First In First Out (FIFO) order
structure in which the element that is 
inserted first is the first one to be taken out. 

| Operation | Average Time complexity | Worst Time complexity |
| --------- | --------------- | -------- |
| Access    | O(n)            |  O(n)    |
| Insert    | O(1)            |  O(1)    |
| Search    | O(n)            |  O(n)    |
| Delete    | O(1)            |  O(1)    |
<br>
<br>

> ## **TREES**


> ## **GRAPHS**
 
Unlike other common data structures, a graph consist of vertices (V) and edges (E).
Thus:

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(V + E)        |
| Insert    | O(1)            |
| Search    | O(V + E)        |
| Delete    | O(E)            |
<br>
<br>

## Algorithms

| Algorithm | Time Complexity |
| --------- | --------------- |
