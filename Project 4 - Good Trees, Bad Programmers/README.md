# 🌳 Project – Heap & Binary Search Tree Testing (Spring 2025)

This project focuses on **testing and understanding tree data structures**: Heaps and Binary Search Trees (BSTs). I wrote **JUnit test cases** for a pre-written Priority Queue (Heap) and a Binary Search Tree implementation. This project strengthened my ability to read and test existing code, connect theory to implementation, and write meaningful tests for data structures I had not written before.

---

## 🔧 Key Components

- `PriorityQueue.java` – A max-heap implementation of a priority queue.
- `BinarySearchTree.java` – A fully implemented Binary Search Tree with core operations.
- `BinaryNode.java` – Internal representation of nodes for the BST.
- `BinaryTreeIterator.java` – An iterator for in-order traversal of the BST.
- `AbstractCollection.java` – Abstract base class for collections with basic properties.
- `Collection.java` – Interface defining basic collection operations.
- `DuplicateItemException.java` – Exception thrown when adding a duplicate value to the BST.
- `ItemNotFoundException.java` – Exception thrown when trying to remove a non-existent item.

---

## 📌 Features

- Test `PriorityQueue` operations such as `add()`, `element()`, `remove()`, and heap ordering
- Test `BinarySearchTree` operations such as `insert()`, `remove()`, `findMin()`, `findMax()`, and `iterator()`
- Catch and validate custom exceptions like `DuplicateItemException` and `ItemNotFoundException`
- Confirm correct behavior of tree traversal through iterator tests

---

## 📁 Project Files

- `AbstractCollection.java`  
- `BinaryNode.java`  
- `BinarySearchTree.java`  
- `BinaryTreeIterator.java`  
- `Collection.java`  
- `DuplicateItemException.java`  
- `ItemNotFoundException.java`  
- `MyTestsBST.java`  
- `MyTestsPQ.java`  
- `PriorityQueue.java`  

---

## ✅ Skills Demonstrated

- Reading and understanding existing codebases  
- Writing comprehensive unit tests using JUnit  
- Testing behavior of tree structures and iterators  
- Exception handling and test case validation  
- Command-line compilation and test execution using `javac` and `java`  
- Understanding of heaps and binary search tree properties  

---

## 🧪 Testing Strategy

- Use JUnit 4.11 for structured, timeout-based tests  
- Validate expected behavior of core operations in both Heap and BST  
- Confirm correct traversal and ordering in data structures  
- Ensure proper exception handling for invalid operations  
- Include a variety of edge cases such as:
  - Empty data structures
  - Boundary conditions
  - Duplicate entries
  - Minimum and maximum value handling
  - Structural changes after insertions or deletions

---
