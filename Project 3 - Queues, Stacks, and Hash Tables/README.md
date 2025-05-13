# 🖥️ Postfix Computer – Expression Evaluator (Spring 2025)

This project simulates a **Postfix Expression Evaluator** using custom **queues**, **stacks**, and **hash tables**. The system supports evaluating postfix expressions, performing basic mathematical operations, and managing variable assignments. It provides an excellent opportunity to practice data structure manipulation, file I/O, and debugging.

---

## 🔧 Key Components

- `Computer.java` – Main class responsible for processing postfix programs, evaluating expressions, and handling debug mode.
- `Node.java` – Represents the node structure used for queue and stack operations.
- `ProgramStack.java` – Custom stack implementation using a linked list to support basic stack operations.
- `SymbolTable.java` – Hash table implementation for variable assignments using quadratic probing.
- `MapInterface.java` – Interface defining essential methods for map-like data structures.
- `StaticArray.java` – A static array implementation used for managing basic data operations in the program.
- `ThreeTenMap.java` – Hash map implementation for the `SymbolTable` to store and retrieve variables efficiently.
- `ThreeTenMapEnhanced.java` – Enhanced version of `ThreeTenMap`, adding additional functionalities.
- `ThreeTenMapEntry.java` – Represents the individual entry within the map structure, holding key-value pairs.
- `sample1.txt` / `sample2.txt` – Example postfix programs for testing.

---

## 📌 Features

- **Postfix Expression Evaluation**: Supports basic arithmetic operations (`+`, `-`, `*`, `/`) and `print` command.
- **Variable Assignment**: Variables can be assigned and used in postfix expressions, supporting operations like `=`, `+=`, `-=`, `*=`, `/=`.
- **Debug Mode**: Provides step-by-step trace of the execution, showing the state of the stack, symbol table, and remaining program.
- **File I/O**: Reads postfix expressions from text files for easy testing and execution.
- **Custom Data Structures**: Implements custom queue, stack, and hash table classes to manage program data and state.

---

## 📁 Project Files

- `Computer.java` – Main class to handle the postfix expression evaluation logic.
- `MapInterface.java` – Interface for map-related data structure methods.
- `Node.java` – Node class supporting the queue and stack implementations.
- `ProgramStack.java` – Custom stack implementation using a linked list for stack operations.
- `StaticArray.java` – Static array implementation for handling data.
- `SymbolTable.java` – Hash table for storing variables and their assignments.
- `ThreeTenMap.java` – Standard hash map for efficient variable storage and retrieval.
- `ThreeTenMapEnhanced.java` – Enhanced version of the `ThreeTenMap` with added functionality.
- `ThreeTenMapEntry.java` – Represents key-value pairs in the hash map.
- `sample1.txt` (Test Postfix Program) – Example postfix program for testing.
- `sample2.txt` (Test Postfix Program) – Another example postfix program for testing.

---

## ✅ Skills Demonstrated

- Queue and stack data structure implementation using linked lists.
- Hash table implementation with quadratic probing for efficient variable storage.
- Postfix expression evaluation algorithm.
- File reading and writing for program input and output.
- Debugging and error handling in step-by-step execution mode.
- JavaDoc and Code Documentation for clarity and maintainability.

---

## 🧪 Testing Strategy

- **File-based Testing**: Programs are read from text files, tested for correctness by printing the evaluated results.
- **Debug Mode**: Enables detailed step-by-step testing and validation of program execution.
- **Edge Case Testing**: Includes testing for invalid expressions, division by zero, and variable assignment errors.
- **Unit Testing**: Verifies correctness of individual methods for stack operations, queue processing, and hash table lookups.

---