# Assignment 03: Arrays & Algorithm Analysis
**Data Structures and Algorithms (TKU211231)**

---

## Student Information

- **Name:** Zahwa Agroli
- **Student ID:** 24/535089/TK/59335
- **Department:** Electrical and Information Engineering, Universitas Gadjah Mada

---

## Description

- **Problem 2 (DynArray):** Implemented a procedural resizable array using a `struct` with manual heap allocation, doubling capacity upon overflow, and providing functions for element manipulation (`insertAt`, `removeAt`, etc.).
- **Problem 3 (Search Algorithms):** Developed and compared iterative Linear Search and Binary Search algorithms, demonstrating their performance across different array sizes (*n* = 10, 100, 1000).
- **Written Analysis (Problems 1, 3B, 4):** Provided a detailed PDF analysis of operation counts (*T(n)*), Big-O complexity tables for search types, and a formal amortized cost proof for the doubling growth strategy.

---

## Compilation Commands
```bash
# Compile Problem 2
g++ -std=c++17 -Wall -Wextra -g -fsanitize=address problem2.cpp -o problem2

# Compile Problem 3
g++ -std=c++17 -Wall -Wextra -g -fsanitize=address problem3.cpp -o problem3
```

---

## Known Issues or Limitations

- Both programs compile successfully without any memory leaks when tested with AddressSanitizer.
- All functions assume that the provided indices are within the valid range (0 ≤ index < size) as per the assignment constraints.
- Binary search is only applicable to sorted arrays.

---

## Time Spent on the Assignment

**Total: 12 hours**
