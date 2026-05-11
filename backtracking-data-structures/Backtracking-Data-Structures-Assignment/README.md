# Backtracking---Data-Structures-Assignment
Data Structures -- Assignment 2 (Backtracking)

This repository contains my solution for Assignment 2 in the Data Structures course.

Java -- Backtracking Algorithms & Dynamic Set ADT

---

## Overview

This project focuses on **backtracking algorithms and data structures**, including the ability to undo and redo operations.

The assignment combines:
- Algorithm design
- Data structure implementation
- Backtracking techniques
- Runtime and space complexity analysis

According to the assignment :contentReference[oaicite:0]{index=0}, the goal is to implement efficient backtracking-based structures and algorithms while maintaining correctness and invariants.

---

## What Was Required

### 1. Backtracking Algorithms

- Implement search algorithms with backtracking:
  - `backtrackingSearch` on an unsorted array
  - `consistentBinSearch` with consistency checks
- Use a **stack ADT** to undo steps
- Maintain correctness invariants during execution

---

### 2. Backtracking Dynamic Set ADT

Implement a dynamic set with full functionality:

- `search`
- `insert`
- `delete`
- `minimum`
- `maximum`
- `successor`
- `predecessor`
- `print`
- `backtrack` (undo last operation)

---

### 3. Multiple Implementations

The dynamic set had to be implemented using:

- Unsorted array
- Sorted array
- Binary Search Tree (BST)

---

### 4. Advanced Backtracking (Redo Support)

- Implement `retrack` (redo operation)
- Support undo/redo behavior similar to real systems
- Use stacks to track operations

---

### 5. Complexity Analysis

- Analyze runtime of backtracking operations
- Analyze space complexity (e.g., tree traversal)

---

## What I Implemented

- Implemented `backtrackingSearch` using a stack to simulate forward/backward steps
- Implemented `consistentBinSearch` with dynamic consistency checks and backtracking
- Built a full **Backtracking Dynamic Set ADT** supporting all required operations
- Implemented the ADT using:
  - Unsorted array
  - Sorted array
  - Binary Search Tree (BST)
- Implemented `backtrack` to undo insert/delete operations
- Implemented `retrack` to redo operations after backtracking
- Ensured all operations maintain correctness invariants
- Implemented efficient search, insert, and delete operations for each structure
- Implemented correct output formatting for both array and BST structures
- Completed runtime and space complexity analysis

---

## Features

- Backtracking support (undo operations)
- Redo functionality (`retrack`)
- Multiple data structure implementations
- Stack-based operation tracking
- Efficient and modular design
- Correct handling of edge cases

---

## Build & Run

Compile and run using your Java environment (e.g., VPL or local IDE)

---

## Environment

Java  
Stack ADT (provided by course)

---

## Notes

- Focus on algorithm correctness and efficiency
- Emphasis on backtracking and dynamic data structures
- Designed to simulate real-world undo/redo systems
