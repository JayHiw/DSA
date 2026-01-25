# DSA This repository contains my journey of learning **Data Structures and Algorithms (DSA)** using **Python**.
 Language Used - Python   ## Goal To build strong problem-solving skills and maintain consistency through daily practice.  ---

## What’s Inside?
- Core DSA concepts
- Clean and beginner-friendly Python implementations
- Important problems with explanations
- Structured topic-wise folders

01_time_complexity.md

What is Time Complexity

Big O, Big Ω, Big Θ

Common complexities:

O(1), O(log n), O(n), O(n log n), O(n²)

Simple examples (loops, nested loops)

Linear Search → O(n)
Linear Search (element at first index) → Ω(1)
Binary Search → Θ(log n)
O(1) – Constant Timedef get_first_element(arr):
    return arr[0]
O(n) – Linear Timedef print_elements(arr):
    for i in arr:
        print(i)
O(n²) – Quadratic Timedef print_pairs(arr):
    for i in arr:
        for j in arr:
            print(i, j)
Repository Structure Update

Organized DSA repo for long-term scalability

Separated:

Theory notes (.md)

Code examples (.py / .c)

Prepared base for upcoming topics:

Arrays

Recursion

Searching & Sorting
Add time complexity theory with examples and structured notes
heres an example for 2 d array
arr = [10, 20, 30, 40, 50]

for i in range(len(arr)):
    print(arr[i])

to do 
DSA/
│
├── 00_Basics/
│   ├── 01_time_complexity.md
│
├── 01_Arrays/
│   ├── array_traversal.py
│
├── 02_Recursion/
│
├── 03_Searching_Sorting/
│
└── README.md

# DSA – Data Structures & Algorithms in Python

This repository documents my journey of learning **Data Structures and Algorithms (DSA)** using **Python**.

The goal is simple:
build strong problem-solving skills and stay consistent through daily practice.

---

## Language Used
DSA/
│
├── 00_Basics/
│   └── 01_time_complexity.md
│
├── 01_Arrays/
│   └── array_traversal.py
│
├── 02_Recursion/
│
├── 03_Searching_Sorting/
│
└── README.md


