# EECS 280 WN 2021 Final Learning Objectives

This document contains student-written responses to Sections 11-19 of the learning objectives listed [here](./media/Final_Learning_Objectives.pdf). For Sections 1-10, see [Midterm Learning Objectives](../midterm/midterm.md). Responses here are a combination of

1. Paraphrased explanations and summaries, and
2. Notes taken verbatim from [Prof. Amir Kamil's EECS 280 Lecture Notes](https://eecs280staff.github.io/notes/).

Table of Contents: GitHub now has built-in TOC at the top left of the Markdown preview.

## 11. Dynamic Memory

### a. Understand the difference between the stack and the heap

### b. What the stack and heap look like in memory (memory model)

### c. Understand how the scope of dynamic memory variables can be controlled

### d. Identify use of dynamic memory in code

### e. Understand that the ‘new’ operator allocates space in the heap and evaluates to its address

### f. Know when the delete operator should be used and how to use it

### g. Create and use dynamic arrays

#### i. Be able to use the specific delete[] operator when deleting dynamic arrays

#### ii. Be able to identify when it is needed to iterate through a dynamic array to delete elements in the array

### h. Follow the scope of an object and identify where it is created/destroyed (ex. writing ctor and dtor print statements in the correct order)

### i. Identify and correct dynamic memory errors

#### i. Double free, memory leak, etc.

### j. Develop code that uses dynamic memory and prevents memory leaks and other errors

### k. Draw memory diagrams with dynamic memory (drawing the heap)

### l. Be able to explain RAII, and why using RAII is beneficial

### m. Develop code that makes use of RAII

## 12. The Big Three

### a. Be able to identify classes which need custom implementations of the big three

### b. Be able to correctly implement the big three if needed

### c. Be able to explain the difference between shallow and deep copies

### d. Be able to explain why destructors should be marked as virtual in classes that make use of inheritance

### e. Identify errors in big three implementations or shallow copies and how they could cause dynamic memory errors later on

### f. Understand what the default, compiler generated versions of the big three do

## 13. Containers and Templates

### a. Be able to identify time complexities of insert, find and remove for both Sorted and Unsorted Sets

### b. Be able to explain an advantage of using templates when defining the interface for a container

### c. Be able to use templates properly

### d. Be able to identify various types of containers and each underlying functionality (i.e. some containers have member functions like push_back())

### e. Be able to use various types of containers when given a problem

### f. Be able to explain why operator overloading is necessary

### g. Be able to write an implementation of an operator overload

## 14. Recursion

### a. Be able to identify recursion, tail recursion, tree recursion, and structural recursion problems

### b. Be able to write a recursive function given a problem

#### i. Break down problem into smaller sub-problems

### c. Understand how to write a structural recursive function

### i. Break down data structures into smaller data structures

### d. Be able to write an appropriate base case given a problem

### e. Be able to differentiate between the memory complexity of normal linear recursive functions and tail recursive functions

### f. Be able to draw a memory diagram of the stack given a recursive function call

### g. Convert iteration into recursion and recursion into iteration

### h. Understand when to use recursion vs. iteration

## 15. BSTs

### a. Be able to identify the difference in time complexities between removing, inserting, and finding an item in a BST vs an Unsorted Set and a Sorted Set

#### i. Best case, worst case, and average case

### b. Be able to draw a BST representation in memory with pointers

### c. Be able to use recursion to implement functions such as insert, find, and height for a BST

### d. Be able to identify whether the big three is needed for a BST (and why) and properly implement the big three using recursion in a BST interface

### e. Be able to write preorder and inorder traversals of BSTs

### f. Be able to identify and explain the stack frame creation/destruction when using recursive functions in a BST

## 16. Iterators and Functors

### a. Be able to traverse through a container with an iterator

### b. Be able to identify scenarios in which an iterator can be invalidated

### c. Be able to explain the concept of an end iterator

### d. Be able to define what a functor is

### e. Be able to identify at least one advantage in using functors

### f. Be able to use a functor in code

### g. Be able to define what a predicate is

### h. Be able to define what a comparator is

### i. Be able to write a predicate

### j. Be able to write a comparator

### k. Be able to identify that range based for loops are effectively the same as traversal by iterator

### l. Iterators are meant to provide a standardized interface for traversing through different types of containers

#### i. Know when to dereference an iterator

### m. Know how to iterate through a container using iterators

### n. Understand why iterators should not implement the big three, even though they reference to dynamic memory

### o. Be able to define what a function pointer is

### p. Be able to use a function pointer in code

## 17. Linked Lists

### a. Be able to identify at least two differences between using a linked list and a vector

### b. Be able to draw a linked list representation in memory

### c. Be able to declare a linked list iterator

### d. Be able to use a linked list iterator

### e. Be able to define friend classes

### f. Be able to use friend classes

### g. Be able to add and delete nodes into the linked list without creating any memory errors

### h. Perform operations on linked lists without errors (chopping a list, stretching)

### i. Explain how linked lists are recursive data structures

### j. Explain why iterators are necessary for traversing a linked list

### k. Explain why linked lists are better (have faster time complexity) than arrays/vectors for certain operations (removing from the top, middle)

## 19. Impostor Syndrome

### a. Be able to identify common characteristics of impostor syndrome

### b. Be able to identify steps that can be taken to overcome impostor syndrome

### c. Understand that most individuals feel imposter syndrome at some points in their careers

### d. Understand that certain groups of individuals are more prone to feeling imposter syndrome through their careers
