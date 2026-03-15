# Linked List Implementation (CENG 218 Data Structures Lab)

## Overview

This project implements a **singly linked list in C++** as part of the **CENG 218 Data Structures** laboratory assignment (2025–2026 Spring).

The implementation provides common linked list operations such as insertion, deletion, element access, copying, comparison, and traversal. Additionally, extra functions were implemented to analyze and manipulate nodes within the list.

A **menu-driven console interface** is included to allow interactive testing of all linked list operations.

---

## Features

### Basic Linked List Operations

* `push_front()` – Insert element at the beginning
* `push_back()` – Insert element at the end
* `insert_at()` – Insert element at a specific index
* `insert_after()` – Insert element after a given index

### Removal Operations

* `pop_front()` – Remove the first element
* `pop_back()` – Remove the last element
* `erase_at()` – Remove element at a given index
* `erase()` – Remove the first occurrence of a value
* `clear()` – Delete all nodes

### Element Access

* `front()` – Access the first element
* `back()` – Access the last element
* `at()` – Access element at a specific index

### Capacity Functions

* `size()` – Returns number of nodes
* `empty()` – Checks whether the list is empty

### Operator Overloads

* `operator=` – Assignment operator (deep copy)
* `operator==` – List comparison
* `operator<<` – Stream output for printing list contents

---

## Additional Features

### 1. Find Middle Node

`findMiddleNode()`

Returns the **middle node** of the linked list.

* If the list has an **odd number of nodes**, the exact middle node is returned.
* If the list has an **even number of nodes**, the **second middle node** is returned.
* Returns `nullptr` if the list is empty.

---

### 2. Find Smallest Node

`getSmallestNode()`

Returns the node containing the **lexicographically smallest string** in the list.

* Returns `nullptr` if the list is empty.

---

### 3. Move Smallest Node to Front

`moveSmallestToFront()`

Finds the smallest node and moves it to the **front of the linked list**.

Edge cases handled:

* Empty list
* Single-node list

---

## File Structure

```
.
├── Node.h
├── LinkedList.h
├── LinkedList.cpp
├── main.cpp
└── README.md
```

**Node.h**

* Defines the `Node` class used in the linked list.

**LinkedList.h**

* Declares the `LinkedList` class and all its methods.

**LinkedList.cpp**

* Contains the implementation of linked list operations.

**main.cpp**

* Menu-driven program to test linked list functionality.

---

## Example Output

```
1. Push Back
2. Push Front
3. Insert At
4. Pop Back
5. Pop Front
6. Erase At
7. Print List
8. Find Middle Node
9. Get Smallest Node
10. Move Smallest To Front
0. Exit
```

---

## Concepts Used

* Singly Linked List
* Dynamic Memory Management
* Deep Copy
* Operator Overloading
* Pointer Manipulation
* Menu-driven CLI program

---

## Author

CENG 218 – Data Structures
Computer Engineering Lab Assignment
2025–2026 Spring
