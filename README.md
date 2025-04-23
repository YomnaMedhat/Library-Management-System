# Library Management System in C++

A console-based C++ application that allows users to manage a library of Fiction and Non-Fiction books using object-oriented programming (OOP) and standard data structures like stacks, queues, and linked lists.

---

## Features

- Add, search, remove, and display Fiction and Non-Fiction books
- Track recently added books using a Stack (Last-In-First-Out, max 5 entries)
- Maintain a borrowing history using a Queue (First-In-First-Out, max 10 entries)
- Uses OOP principles: Inheritance, Encapsulation, and Polymorphism
- Book attributes: Title, Author, and ISBN
- Interactive console-based menu

---

## File Structure

- `main.cpp`: Contains all source code for the library system
- No external dependencies or libraries required

---

## Data Structures Used

- Singly Linked List – for managing Fiction books
- Doubly Linked List – for managing Non-Fiction books
- Stack – for recently added books
- Queue – for borrowing history

---

## How to Compile and Run

Make sure you have a C++ compiler like `g++` installed.

### Compile:
```bash
g++ main.cpp -o library

Menu Options
Add Fiction Book

Add Non-Fiction Book

Display Fiction Books

Display Non-Fiction Books

Search Fiction Book

Search Non-Fiction Book

Remove Fiction Book

Remove Non-Fiction Book

Borrow a Book

Display Recently Added Books

Display Borrowing History

Exit

Limitations
No persistent storage or file handling (data is lost after program ends)

ISBNs are not validated for format or uniqueness

Basic input validation only

Console-based UI only

Author
Developed by Yomna Medhat, 2024
