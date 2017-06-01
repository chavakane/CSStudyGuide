# Data Structures
In computer science, a data structure is particular way of organizing data in a computer so that it can be used efficiently.

## Arrays
### Array
Array is a data structure used to store elements in contiguous locations. Size of an array must be provided before storing data.

Data can be retrieved in a constant time [ O(1) ] if the index is known. 



### Dynamic Array
Is an array that can grow during runtime, generally by doubling its size when the array's capacity has been filled.

The insertion times are generally fast, but they are slow when the array has to increase it's size.

When the array increases it's size, a new array is created and the data of the old array is copied to the new one.
### Matrix
Commonly known as a two-dimension array.
### String
In some languages, like C, a string is represented as an array of characters.

## Lists
### Linked List
Is a data structure consiting of nodes that contain a value or values and a reference/pointer to another node. 

The advantages of this against an array is that it can grow dynamically. 

The disadvantage is that is not indexed and 
### Doubly Linked List
### Circular Linked List
### Stack
### Queue

## Hash Table
A hash table is a data structure that maps keys to values for highly efficient lookup.

Hash Tables can be implemented in different ways, a common implementation is by using an array of linked lists and a hash code function.

1. The hash code function transforms the key into a numeric value. The numeric value is known as hash code. Two different keys could generate the same hash code.
2. Map the hash code to an index in the array. Since the array has a finite number of indexes, this could be done with something like: ``` hash(key) % array_length ```. Two different hash codes could map to the same array index.
3. At this index, there is a linked list of keys and values. Store the key and value in this index. A linked list is used to avoid collisions, since you could have two or more keys mapped to the same hash code, or two or more hash codes mapped to the same index.


## Trees
### Binary Tree
### B - Tree
## Graph

