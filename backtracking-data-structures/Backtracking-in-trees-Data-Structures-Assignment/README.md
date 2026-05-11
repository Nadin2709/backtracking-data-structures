# -Backtracking-in-trees---Data-Structures-Assignment
Data Structures -- Assignment 4 (Backtracking in Trees)

This repository contains my solution for Assignment 4 in the Data Structures course.

Java -- Backtracking in B-Trees and AVL-Trees

---

## Overview

This project focuses on extending tree data structures with **backtracking capabilities**, allowing undo operations on insertions.

The assignment combines:
- Advanced tree data structures (B-Tree, AVL Tree)
- Backtracking techniques
- Order-statistics operations
- Time and space complexity analysis

According to the assignment :contentReference[oaicite:0]{index=0}, the goal is to efficiently support undo operations while maintaining correct tree structure and performance guarantees.

---

## What Was Required

### 1. Backtracking in B-Trees

- Given a partial B-Tree implementation (insert, split, search)
- Implement:
  - `Backtrack(S)` → undo last insertion
- Constraints:
  - Use only Θ(h) extra information (h = tree height)
- Provide:
  - A counterexample where backtracking ≠ delete

---

### 2. Backtracking in AVL Trees

- Given AVL Tree with insertion and balancing
- Extend it to support:
  - `Backtrack(S)` → undo last insertion
  - `Select(i)` → i-th smallest element
  - `Rank(val)` → number of elements smaller than val

Constraints:
- Use only Θ(1) extra information per insertion
- Maintain O(log n) time complexity for operations

---

### 3. Theoretical Analysis

- Analyze:
  - Time complexity of backtracking
  - Space complexity of stored information
- Compare different approaches (e.g., full-copy vs efficient tracking)

---

## What I Implemented

### B-Tree

- Implemented `Backtrack(S)` for undoing insert operations
- Stored minimal information per insertion (O(h))
- Handled node splits and structural changes correctly
- Provided a valid counterexample showing difference from delete

---

### AVL Tree

- Implemented `Backtrack(S)` using efficient tracking of changes
- Extended tree to support:
  - `Select(i)` in O(log n)
  - `Rank(val)` in O(log n)
- Stored additional metadata (e.g., subtree sizes)
- Maintained AVL balancing after operations

---

### Design & Efficiency

- Ensured all operations maintain tree invariants
- Used minimal extra memory as required:
  - O(h) for B-Tree
  - O(1) per insertion for AVL
- Implemented efficient undo logic without copying full structures

---

## Features

- Backtracking (undo insert operations)
- Order-statistics operations (Select & Rank)
- Efficient tree updates and balancing
- Multiple data structure implementations
- Correct handling of edge cases

---

## Build & Run

Compile and run using Java (VPL or local IDE)

---

## Environment

Java  
List / Deque (allowed by assignment)

---

## Notes

- Focus on efficient data structure design
- Emphasis on correctness and performance
- Demonstrates advanced tree manipulation and undo mechanisms
