## **Phase 1: The Syntax Sprint**
**Goal:** Get comfortable with the Python "dictionary" so you can speak the language. Don't worry about memory or efficiency yet.

*   **Variables & Data Types:** Integers, Floats, Strings, Booleans.
*   **Data Structures:** Lists, Dictionaries, Tuples, Sets (Focus on how to access and change data).
*   **Control Flow:** `if/else` logic and `for/while` loops.
*   **Functions:** Arguments, return values, and scope.
*   **The "Why":** Learn the difference between Interpreted and Compiled languages.
*   **Project 1:** **The Smart CLI Calculator.** Don't just do $1 + 1$. Create a program that takes user input, stores a history of calculations in a List, and allows the user to clear it.

---

## **Phase 2: CS Fundamentals (The "Under the Hood" Era)**
**Goal:** Transition from writing scripts to understanding the machine.

*   **Memory Management:** How Python handles objects. Understand the **Stack vs. Heap** and how "Pointers" work (even though Python hides them).
*   **Binary & Logic Gates:** Learn how `0` and `1` represent data. Understand bitwise operators (`&`, `|`, `^`).
*   **Time Complexity (Big O Notation):** Why is a Dictionary faster than a List for searching? Learn to measure your code's performance.
    
*   **Object-Oriented Programming (OOP):** Classes, Inheritance, and Encapsulation.
*   **Project 2:** **A Custom Library Management System.** Build this using OOP. Use a "Book" class and a "Library" class. Implement a search feature and analyze if your search is $O(n)$ or $O(1)$.

---

## **Phase 3: Algorithms & Data Structures (The Logic Era)**
**Goal:** Solve complex problems efficiently.

*   **Recursion:** Understanding the Call Stack (how functions call themselves).
*   **Sorting & Searching:** Implement Bubble Sort (to understand why it's slow) and Merge Sort (to understand why it's fast).
*   **Linked Lists & Trees:** Build a simple Tree structure from scratch to understand non-linear data.
*   **The "Why":** Understand how Python’s internal `sort()` (Timsort) actually works.
*   **Project 3:** **A File Navigator.** Write a script that traverses your computer's folders (a tree structure) using recursion and finds files based on specific extensions.

---

## **Phase 4: Systems & Networking**
**Goal:** Understand how computers talk to each other.

*   **The Request/Response Cycle:** How the internet works (HTTP, DNS, IP).
*   **Concurrency vs. Parallelism:** Using `threading` and `multiprocessing`. Understand the **Global Interpreter Lock (GIL)** in Python.
*   **Database Fundamentals:** SQL vs. NoSQL. How data is persisted on a disk.
*   **Project 4:** **Multi-threaded Web Scraper.** Build a tool that scrapes multiple websites simultaneously, stores the data in a SQL database, and uses a hashing algorithm to ensure no duplicate entries are saved.

---

## **Phase 5: The Architectural Capstone**
**Goal:** Build a production-ready application.

*   **API Design:** Using frameworks like FastAPI or Flask.
*   **Testing & Debugging:** Writing Unit Tests and using the Python Debugger (`pdb`).
*   **Environment & Deployment:** Virtual environments, Docker, and CI/CD basics.
*   **Final Project:** **A Real-time Task Manager.** 
    *   **Backend:** Python/FastAPI.
    *   **CS Focus:** Implement a "Priority Queue" (Data Structure) to handle tasks based on urgency.
    *   **Persistence:** Use a database to save tasks.
    *   **Efficiency:** Ensure all API endpoints are optimized for speed.

---

### **How to use this roadmap:**
1.  **Don't get stuck in tutorial hell.** If you learn about "Loops" today, write a loop today. 
2.  **Read the Source:** When you use a Python module, occasionally "Ctrl + Click" on a function to see how it was written by the pros.
3.  **Break things:** You learn more about the Call Stack by causing a `RecursionError` than you do by writing perfect code.
