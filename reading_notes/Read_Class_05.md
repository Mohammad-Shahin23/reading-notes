# Class Reading 04 

## Big O: Analysis of Algorithm Efficiency
    Big O notation is a way to measure how good an algorithm or function is at doing a task. 
    It looks at how much time and memory the algorithm needs to work. Input Size is how much data the algorithm is working with. Orders of Growth is how much more time or memory the algorithm needs when it has more data. 
    We should always look at how much space and time an algorithm needs separately. Nowadays, computers have a lot of memory, so we don't need to worry as much about how much memory an algorithm uses.

## Linked Lists

   A linked list is a data structure that consists of nodes, each with data and a reference to the next node. 
   A singly linked list has one reference, while a doubly linked list has two. The head is the first node and the last node has a reference to null. 
   To traverse a linked list, use a while loop to move from one node to the next using the next reference. 
   Adding a node with O(1) efficiency requires setting the next reference of the new node to the current head and then setting the head to the new node.

## What’s a Linked List, Anyway? [Part 1]

    this article is talking about static and dynamic data structures. Static data structures like arrays have a fixed size and if you need to add more elements to it, you'll need to allocate a new block of memory with a larger size and copy all of the existing elements over. 
    This can be slow and inefficient, especially for large data sets. Dynamic data structures like linked lists, on the other hand, can grow and shrink as needed because they don't require a fixed amount of memory to be allocated when they are created. Linked lists are constructed dynamically as elements are added or removed, which can make them more efficient and flexible for certain types of operations.

## What’s a Linked List, Anyway? [Part 2
This article talks about Big O notation, which is used to measure how well an algorithm performs. It considers the speed and efficiency of an algorithm as the size of the input grows. There are two things to consider when analyzing the performance of an algorithm: how much time it takes and how much memory it uses. When dealing with linked lists, there are two types of Big O equations to remember: O(1) and O(n). The article also explains how linked lists work, how to add and remove elements from them, and how they differ from arrays.]

