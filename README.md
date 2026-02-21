# Data Structures and Algorithms

A comprehensive learning resource for mastering core DSA concepts, progressing from fundamentals to advanced algorithms and problem-solving techniques.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Difficulty Levels](#difficulty-levels)
- [Topics Covered](#topics-covered)
  - [Beginner Level](#-beginner-level)
  - [Intermediate Level](#-intermediate-level)
  - [Advanced Level](#-advanced-level)
- [Learning Path](#learning-path)
- [How to Use](#how-to-use)

---

## Overview

This repository contains implementations and explanations of fundamental and advanced data structures and algorithms. Each topic includes:
- ✅ Algorithm implementations in Python
- 📝 Detailed explanations
- 🔍 Time and Space complexity analysis
- 💡 Practical examples

---

## Difficulty Levels

| Level | Description | Prerequisites |
|-------|-------------|----------------|
| **Beginner** 🟢 | Foundation concepts, basic data structures | Basic Python knowledge |
| **Intermediate** 🟡 | Complex algorithms, optimization techniques | Beginner concepts mastered |
| **Advanced** 🔴 | Optimization, competitive programming | Intermediate concepts mastered |

---

## Topics Covered

### 🟢 Beginner Level

#### 1. [Sorting Algorithms](Bubblesort/)
- **Topic**: [Bubble Sort](Bubblesort/Bubble.py)
- **Concepts**: Comparison-based sorting, adjacent element swaps
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)
- **Use Cases**: Small datasets, educational purposes
- **Practice Questions**:
    - Sort an array using bubble sort
    - Implement optimized bubble sort with early termination
    - Count swaps during bubble sort
    - Bubble sort with a custom comparator
- **Next Level**: → [Merge Sort (Intermediate)](MergeSort/merge.py)

#### 2. [Selection Sort](SelectionSort/)
- **File**: [selection.py](SelectionSort/selection.py)
- **Concepts**: Finding minimum element, in-place sorting
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)
- **Practice Questions**:
    - Sort an array using selection sort
    - Find the k smallest elements using selection logic
    - Implement selection sort for descending order
    - Selection sort variant counting element frequencies
- **Next Level**: → [Merge Sort (Intermediate)](MergeSort/merge.py)

#### 3. [Recursion Basics](Recursion/)
- **File**: [recursion.py](Recursion/recursion.py)
- **Concepts**: Base case, recursive calls, call stack
- **Applications**: Tree traversal, backtracking
- **Practice Questions**:
    - Calculate factorial recursively
    - Sum of digits of a number using recursion
    - Implement power function (a^b) recursively
    - Count occurrences of a digit in a number
    - Reverse a string using recursion
    - Print binary representation of a number
- **Next Level**: → [Dynamic Programming (Intermediate)](DP/Dp.py)

#### 4. [Time and Space Complexity](Time%20And%20Space/)
- **File**: [time.py](Time%20And%20Space/time.py)
- **Concepts**: Big O notation, asymptotic analysis, complexity classes
- **Essential For**: Algorithm optimization, interview preparation
- **Practice Questions**:
    - Analyze time complexity of nested loops
    - Identify space complexity of recursive functions
    - Compare O(n) vs O(n²) algorithms and suggest optimizations
    - Optimize an O(n²) algorithm to O(n log n)
    - Determine complexity of recursive factorial and its space use
    - Explain amortized complexity with dynamic arrays
- **Next Level**: → [Advanced Optimization (Advanced)](#-advanced-level)

---

### 🟡 Intermediate Level

#### 5. [Merge Sort](MergeSort/)
- **File**: [merge.py](MergeSort/merge.py)
- **Concepts**: Divide and conquer, merge operation, stable sorting
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(n)
- **Advantages**: Consistent performance, stable sorting
- **Prerequisites**: [Recursion](Recursion/recursion.py)
- **Practice Questions**:
    - Implement merge sort iteratively (bottom-up)
    - Count inversions in an array using merge sort
    - Merge k sorted arrays efficiently
    - Sort a nearly sorted (k-sorted) array
    - Implement merge sort for linked lists
    - Outline external merge sort for large datasets
- **Next Level**: → [Advanced Sorting (Advanced)](#-advanced-level)

#### 6. [Binary Search](BinarySeach/)
- **File**: [Binary.py](BinarySeach/Binary.py)
- **Concepts**: Divide and conquer, sorted array requirement, logarithmic complexity
- **Time Complexity**: O(log n)
- **Space Complexity**: O(1) or O(log n) recursive
- **Variations**: Linear search → Binary search → Ternary search
- **Prerequisites**: Understanding of sorted data structures
- **Practice Questions**:
    - Find an element in a sorted array
    - Find first and last occurrence of a value
    - Search in a rotated sorted array
    - Find minimum in rotated sorted array
    - Floor and ceiling in a sorted array
    - Allocate pages to students (binary search on answer)
    - Painter partition problem (binary search on answer)
- **Next Level**: → [Two Pointer Technique (Intermediate)](TwoPointer/twopointer.py)

#### 7. [Two Pointer Technique](TwoPointer/)
- **File**: [twopointer.py](TwoPointer/twopointer.py)
- **Concepts**: Opposite direction pointers, meeting condition, array manipulation
- **Applications**: Palindrome checking, container with most water, triplet sum
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)
- **Prerequisites**: [Binary Search](BinarySeach/Binary.py)
- **Practice Questions**:
    - Check if array/string is palindrome using two pointers
    - Reverse words in a string in-place
    - Container With Most Water
    - 3Sum and 4Sum problems
    - Remove duplicates from sorted array
    - Dutch National Flag problem (sort 0s,1s,2s)
- **Next Level**: → [Sliding Window (Advanced)](#-advanced-level)

#### 8. [Linked List](Linked%20List/)
- **File**: [ll.py](Linked%20List/ll.py)
- **Concepts**: Node structure, pointer manipulation, list traversal
- **Operations**: Insert, delete, search, reverse
- **Advantages over Arrays**: Dynamic size, efficient insertion/deletion
- **Practice Questions**:
    - Reverse a linked list (iterative & recursive)
    - Detect cycle in a linked list (Floyd's algorithm)
    - Find middle node of a linked list
    - Merge two sorted linked lists
    - Remove nth node from end of list
    - Reorder list (L0 → Ln → L1 → Ln-1)
    - Flatten a multilevel linked list
- **Next Level**: → [Advanced Data Structures (Advanced)](#-advanced-level)

#### 9. [Stack](Stack/)
- **File**: [stack.py](Stack/stack.py)
- **Concepts**: LIFO (Last In First Out), push, pop, peek operations
- **Applications**: Expression evaluation, undo functionality, DFS
- **Implementation**: Array-based or Linked List-based
- **Practice Questions**:
    - Valid parentheses
    - Evaluate postfix (RPN) expression
    - Infix to postfix conversion
    - Next greater element
    - Largest rectangle in histogram
    - Daily temperatures
    - Design a MinStack supporting getMin in O(1)
- **Next Level**: → [Queue & Advanced Stack Problems (Advanced)](Queues/qu.py)

#### 10. [Queue](Queues/)
- **File**: [qu.py](Queues/qu.py)
- **Concepts**: FIFO (First In First Out), enqueue, dequeue, circular queue
- **Applications**: BFS, task scheduling, producer-consumer
- **Variations**: Simple Queue, Circular Queue, Priority Queue, Deque
- **Prerequisites**: [Stack](Stack/stack.py)
- **Practice Questions**:
    - Implement a queue using two stacks
    - Level order traversal (BFS) of a binary tree
    - Sliding window maximum
    - Design LRU Cache using queue + hashmap
    - Rotten oranges (BFS grid problem)
    - Circular queue implementation
- **Next Level**: → [Graph Algorithms (Advanced)](#-advanced-level)

#### 11. [Prefix Sum](PrefixSum/)
- **File**: [prefix.py](PrefixSum/prefix.py)
- **Concepts**: Cumulative sum, range query optimization, preprocessing
- **Time Complexity**: O(n) preprocessing + O(1) queries
- **Applications**: Range sum queries, counting subarrays, 2D matrix queries
- **Practice Questions**:
    - Range sum query implementation
    - Subarray sum equals K (count subarrays)
    - Product of array except self (without division)
    - 2D range sum query (matrix prefix sums)
    - Count subarrays with sum divisible by K
    - Maximum subarray sum variations
    - Running sum of array
- **Next Level**: → [Advanced Array Techniques (Advanced)](#-advanced-level)

#### 12. [Dynamic Programming Basics](DP/)
- **File**: [Dp.py](DP/Dp.py)
- **Concepts**: Memoization, tabulation, optimal substructure, overlapping subproblems
- **Classic Problems**: Fibonacci, Knapsack, Coin Change, Longest Subsequence
- **Approaches**: Top-down (Memoization), Bottom-up (Tabulation)
- **Prerequisites**: [Recursion](Recursion/recursion.py)
- **Practice Questions**:
    - Fibonacci with memoization and tabulation
    - 0/1 Knapsack problem
    - Coin change (minimum coins) problem
    - Longest increasing subsequence
    - Edit distance (Levenshtein distance)
    - Climbing stairs (combinatorics DP)
    - House robber (max non-adjacent sum)
- **Next Level**: → [Advanced DP (Advanced)](#-advanced-level)

---

### 🔴 Advanced Level

#### 13. [Matrix Operations](Matrix/)
- **File**: [martrix.py](Matrix/martrix.py)
- **Concepts**: 2D array manipulation, matrix traversal, space optimization
- **Advanced Topics**: 
    - Spiral traversal
    - Diagonal traversal
    - Matrix multiplication
    - Transposition
- **Applications**: Image processing, game boards, graph representation
- **Prerequisites**: [Prefix Sum](PrefixSum/prefix.py), Arrays
- **Complexity**: O(n×m) for most operations
- **Practice Questions**:
    - Rotate matrix by 90 degrees
    - Spiral matrix traversal
    - Spiral matrix II (generate filled spiral)
    - Set matrix zeros (row/column zeroing)
    - Search in a 2D matrix (sorted rows/cols)
    - Diagonal traversal of matrix
    - Matrix chain multiplication (DP)

#### 14. [Sieve of Eratosthenes](Sieve%20of%20Eratosthenes/)
- **File**: [soi.py](Sieve%20of%20Eratosthenes/soi.py)
- **Concepts**: Prime number generation, optimization using marking, preprocessing
- **Time Complexity**: O(n log log n)
- **Space Complexity**: O(n)
- **Use Cases**: Finding all primes up to N, number theory problems
- **Advantages**: Much faster than individual primality testing for multiple numbers
- **Prerequisites**: Basic loops and arrays
- **Practice Questions**:
    - Generate all primes up to N using sieve
    - Count primes up to a given number
    - Find prime factors of a number
    - Implement segmented sieve for large ranges
    - Query primes in a range efficiently
    - Explore prime counting approximations
    - Verify Goldbach's conjecture for even numbers up to N

#### 15. [Object-Oriented Programming (OOP)](OPPS/)
- **File**: [opps.py](OPPS/opps.py)
- **Concepts**: Classes, objects, inheritance, polymorphism, encapsulation, abstraction
- **Key Principles**:
    - Encapsulation: Data hiding
    - Inheritance: Code reusability
    - Polymorphism: Method overriding
    - Abstraction: Interface simplification
- **Design Patterns**: Singleton, Factory, Observer (implementation examples)
- **Advanced Topics**: Metaclasses, decorators, context managers
- **Prerequisites**: Procedural programming fundamentals
- **Practice Questions**:
    - Design a calculator using OOP principles
    - Implement a bank account system with transactions
    - Create a library management system (classes for Book, Member)
    - Design an LRU cache using OOP (classes + data structures)
    - Implement the Singleton pattern in Python
    - Implement Factory pattern for object creation
    - Implement Observer pattern for event notifications

#### 16. [Advanced Problem-Solving Techniques](index.py)
- **File**: [index.py](index.py)
- **Topics Integrated**:
    - Sliding Window optimization
    - Greedy algorithms
    - Backtracking and pruning
    - Dynamic programming advanced patterns
    - Graph algorithms (DFS, BFS)
    - Bit manipulation
- **Advanced Algorithms**:
    - Graph traversal and shortest path
    - Topological sorting
    - Strongly connected components
    - Advanced DP with bitmasks
- **Practice Questions**:
    - Longest substring without repeating characters (sliding window)
    - Minimum window substring
    - Word break (DP)
    - Letter combinations of a phone number (backtracking)
    - N-Queens problem (backtracking)
    - Sudoku solver (backtracking + pruning)
    - Number of islands (graph DFS/BFS)

---

## Learning Path

### 📋 Recommended Learning Sequence

```
START HERE
    ↓
1. Time & Space Complexity ────→ [Foundation]
    ↓
2. Recursion Basics
    ↓
3. Sorting Algorithms (Bubble, Selection)
    ↓
4. Binary Search ────────────→ [Logarithmic Search]
    ↓
5. Two Pointer Technique
    ↓
6. Merge Sort
    ↓
7. Linked List ──────────────→ [Data Structures]
    ↓
8. Stack & Queue
    ↓
9. Prefix Sum ────────────────→ [Array Optimization]
    ↓
10. Dynamic Programming
    ↓
11. OOP Concepts ──────────────→ [Code Design]
    ↓
12. Matrix Operations
    ↓
13. Sieve of Eratosthenes
    ↓
14. Advanced Problem Solving ───→ [Integration & Mastery]
```

---

## Progression Paths by Goal

### Path A: Interview Preparation
```
Time & Space → Recursion → Sorting → Binary Search → Two Pointer 
→ Linked List → Stack/Queue → DP → Advanced Problems
```

### Path B: Competitive Programming
```
All Beginner Topics → Advanced Sorting → Graph Algorithms 
→ Advanced DP → Number Theory → Bit Manipulation
```

### Path C: System Design Foundation
```
Time & Space → Data Structures → OOP → Advanced Problems 
→ Optimization Techniques
```

---

## 🎯 How to Use

### Setup Instructions

1. **Clone/Navigate to Repository**
   ```bash
   cd /Users/arunkumargiri/Data-Structures-and-Algorithms-DSA-Sem2
   ```

2. **Run Individual Programs**
   ```bash
   python3 [topic_folder]/[file_name].py
   ```
   Example:
   ```bash
   python3 Bubblesort/Bubble.py
   python3 DP/Dp.py
   ```

3. **Run Main Index**
   ```bash
   python3 index.py
   ```

### Study Tips

- ✅ **Understand Before Memorizing**: Focus on WHY an algorithm works
- ✅ **Trace Through Examples**: Use pen and paper to trace execution
- ✅ **Compare Approaches**: Understand tradeoffs between different solutions
- ✅ **Implement from Scratch**: Type code, don't copy-paste
- ✅ **Optimize Gradually**: Start with brute force, then optimize
- ✅ **Practice Variations**: Modify problems after understanding the base case
- ✅ **Time Yourself**: Build coding speed and accuracy

### Complexity Quick Reference

| Algorithm | Best | Average | Worst | Space |
|-----------|------|---------|-------|-------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) | O(1) |
| DFS/BFS | O(V+E) | O(V+E) | O(V+E) | O(V) |
| DP (general) | O(states × transitions) - varies by problem |

---

## 📊 Topics by Difficulty & Prerequisite Map

```
FOUNDATION
├── Time & Space Complexity
└── Recursion Basics

BASIC ALGORITHMS
├── Bubble Sort
├── Selection Sort
└── Binary Search
    └── Two Pointer Technique

DATA STRUCTURES
├── Linked List
├── Stack
├── Queue
└── Matrix Operations

OPTIMIZATION TECHNIQUES
├── Prefix Sum
├── Sliding Window (covered in Advanced)
└── Dynamic Programming
    ├── Fibonacci & Classic Problems
    ├── Knapsack Problems
    ├── String DP
    └── Tree DP

ADVANCED TOPICS
├── Sieve of Eratosthenes
├── OOP Design Patterns
├── Graph Algorithms
├── Bit Manipulation
└── Advanced Problem Integration

MASTERY
└── Combined Problem Solving
    (Using multiple techniques)
```

---

## 💡 Key Insights

### When to Use Each Algorithm

| Scenario | Algorithm | Why |
|----------|-----------|-----|
| Small dataset, learning | Bubble Sort | Simple, visual |
| Finding in **sorted** array | Binary Search | O(log n) efficiency |
| Fixed-size operations on arrays | Two Pointer | O(1) space, O(n) time |
| Dynamic insertion/deletion | Linked List | Efficient operations |
| LIFO requirement | Stack | Natural fit for recursion, backtracking |
| FIFO requirement | Queue | Job scheduling, BFS |
| Finding all primes < N | Sieve | O(n log log n) optimal |
| Overlapping subproblems | Dynamic Programming | Exponential → Polynomial time |
| Need flexibility | OOP | Reusable, maintainable code |

---

## 🎓 Advanced Optimization Checklist

- [ ] Understand problem constraints
- [ ] Identify data structure options
- [ ] Analyze time/space tradeoffs
- [ ] Consider input characteristics
- [ ] Look for overlapping subproblems (DP)
- [ ] Check for monotonic properties (Two Pointer)
- [ ] Evaluate prefix/suffix optimization
- [ ] Consider preprocessing costs
- [ ] Implement, test, optimize

---

## 📚 Related Advanced Topics (Self-Study)

After mastering this curriculum, explore:
- **Graphs**: DFS, BFS, Dijkstra's, Bellman-Ford, Floyd-Warshall
- **Trees**: BST, AVL, Red-Black, Segment Trees, Fenwick Trees
- **Heaps**: Min-heap, Max-heap, Priority Queues
- **Greedy Algorithms**: Activity Selection, Huffman Coding, Kruskal's, Prim's
- **Advanced DP**: Digit DP, Game Theory, Bitmask DP
- **Number Theory**: GCD, LCM, Modular Arithmetic, Chinese Remainder Theorem
- **String Algorithms**: KMP, Z-algorithm, Rabin-Karp, Trie, Suffix Arrays
- **Geometric Algorithms**: Convex Hull, Line Intersection

---

## 🚀 Next Steps After Completion

1. **Solve Practice Problems**: Use LeetCode, HackerRank, CodeChef
2. **Implement Variations**: Modify existing algorithms
3. **Combine Techniques**: Build complex solutions using multiple algorithms
4. **Study Solutions**: Analyze optimal solutions from competitions
5. **Teach Others**: Explain concepts to reinforce learning
6. **Build Projects**: Create real-world applications using these concepts

---

## 📝 Notes

- All implementations are in **Python 3**
- Comments and docstrings explain key concepts
- Time and space complexity documented for each algorithm
- Each file is self-contained and can be run independently

---

## 🔗 Quick Navigation

| Beginner | Intermediate | Advanced |
|----------|--------------|----------|
| [Bubble Sort](Bubblesort/Bubble.py) | [Merge Sort](MergeSort/merge.py) | [Matrix](Matrix/martrix.py) |
| [Selection Sort](SelectionSort/selection.py) | [Binary Search](BinarySeach/Binary.py) | [Sieve](Sieve%20of%20Eratosthenes/soi.py) |
| [Recursion](Recursion/recursion.py) | [Two Pointer](TwoPointer/twopointer.py) | [OOP](OPPS/opps.py) |
| [Time & Space](Time%20And%20Space/time.py) | [Linked List](Linked%20List/ll.py) | [Advanced Index](index.py) |
| | [Stack](Stack/stack.py) | |
| | [Queue](Queues/qu.py) | |
| | [Prefix Sum](PrefixSum/prefix.py) | |
| | [DP](DP/Dp.py) | |

---

## 📈 Progress Tracker

Track your learning:

- [ ] **Beginner Level**: Foundation (4 topics)
- [ ] **Intermediate Level**: Core Algorithms (8 topics)
- [ ] **Advanced Level**: Optimization & Integration (4 topics)

**Total Topics**: 16 comprehensive DSA concepts

---

## ⭐ Tips for Success

1. **Code Daily**: Consistency beats intensity
2. **Understand > Memorize**: Know the "why" behind algorithms
3. **Test Edge Cases**: Null inputs, empty arrays, single elements
4. **Optimize Iteratively**: Start simple, then improve
5. **Review Regularly**: Revisit older topics to reinforce learning
6. **Join Communities**: Engage with DSA learning groups
7. **Build Projects**: Apply knowledge in real applications

---

## 📧 Questions?

Refer to:
- Algorithm comments in source files
- Complexity analysis sections
- Problem variations in each topic
- Official documentation for specific concepts

---

**Happy Learning! 🎯 Master one topic at a time, and you'll become a DSA expert!**
