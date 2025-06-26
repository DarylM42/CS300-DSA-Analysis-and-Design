# CS300-DSA-Analysis-and-Design

Welcome to my CS 300 portfolio submission. This repository highlights key deliverables from two major projects focused on data structures and algorithms. Each artifact demonstrates my ability to analyze performance, apply structured design principles, and write maintainable, efficient C++ code.

---

## 📈 Project One: Runtime and Memory Analysis

**Objective**: Evaluate the runtime and memory characteristics of a data structure-driven solution for course data validation and storage.

**Summary**:  
This project involved parsing a CSV file of Computer Science courses and validating prerequisites while maintaining efficient access. A hash table was used for its constant-time lookup advantages.

- **Runtime**:
  - File parsing: O(n)  
  - Prerequisite validation: O(n × m), where *m* is the number of prerequisites per course  
  - Hash table operations: Average case O(1)

- **Memory**:
  - All course data stored in structured objects and mapped in a hash table  
  - Space complexity remains linear, O(n), with slight overhead for hashing buckets

This analysis helped reinforce key algorithmic trade-offs between time efficiency and memory usage in real-world system design.

---

## 🧮 Project Two: Course Sorting and Search via Binary Search Tree

**Objective**: Create a menu-driven C++ application for advisors to browse and search academic courses in sorted order.

**Summary**:  
This program reads course data from a CSV file and stores it in a **Binary Search Tree (BST)**, ordered by course number. Users can:
- View all courses sorted alphanumerically (via in-order traversal)
- Search for a specific course and see its details
- Load course data dynamically

The BST ensures that insertion and retrieval operations scale efficiently while naturally maintaining sorted order—no separate sorting logic required.

---

## ✍️ Reflection

The core challenge across both projects was designing software that efficiently manages structured data while remaining readable, scalable, and robust. In Project One, I deepened my understanding of data validation and hash table performance. In Project Two, I translated that knowledge into a working system that demonstrates clean traversal and interactive search using a BST.

Through file handling and debugging file path issues, I also sharpened my troubleshooting process and technical independence. These experiences have shifted how I approach program design: I now write with future maintainability in mind, with clearer comments, modular structure, and more deliberate data structure choices.

Both projects have strengthened my confidence in building systems that balance real-world constraints with solid software engineering principles.

---
