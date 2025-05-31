# Module-12: Queue Implementation Using Linked List (Float/Double Data)
This repository contains C programs demonstrating the implementation of a Queue data structure using a Linked List to store floating-point (float/double) numbers. The program includes essential queue operations like enqueue, dequeue, peek, and display.

## Features
Implement a dynamic queue using linked list nodes.

Store floating-point values (using float type).

## Perform operations:

Enqueue: Add element to the rear of the queue.

Dequeue: Remove element from the front of the queue.

Peek: View the front element without removing.

Display: Show all elements in the queue.

## Code Overview
Struct Node: Defines a node containing a float data and pointer to the next node.

Global pointers: front and rear track the start and end of the queue.

Dynamic memory management with malloc and free.

Error handling for empty queue scenarios.

## How to Run
### Clone the repo:
```
git clone https://github.com/Haripriya132006/Module-12.git
```
### Compile the C program:
```
gcc -o queue queue.c
```
### Run the executable:
```
./queue
```
