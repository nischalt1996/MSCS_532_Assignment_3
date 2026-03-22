## MSCS532 Algorithms and Data Structures
# Author : Nischal Tiwari

# Understanding Algorithm Efficiency and Scalability

## Overview
This project focuses on analyzing the efficiency and scalability of two important algorithmic concepts: **Randomized Quicksort** and **Hashing with Chaining**. The goal of this assignment is to understand how algorithms perform under different conditions and how design choices impact performance.

This project was completed as part of the course **Algorithms and Data Structures (MSCS-532)** at the University of the Cumberlands.

---

## Part 1: Randomized Quicksort

### Implementation
- Implemented Randomized Quicksort where the pivot is selected uniformly at random.
- Used a divide-and-conquer approach with recursion.
- Included handling for edge cases such as:
  - Empty arrays
  - Single-element arrays
  - Sorted and reverse-sorted arrays
  - Arrays with duplicate values

### Analysis
- Average-case time complexity: **O(n log n)**
- Worst-case time complexity: **O(n²)** (rare due to random pivot selection)
- Randomization helps avoid consistently poor pivot choices.

### Comparison
- Compared Randomized Quicksort with Deterministic Quicksort (first element as pivot).
- Observations:
  - Deterministic Quicksort performs slightly faster on random input.
  - Performs poorly on sorted and reverse-sorted inputs.
  - Randomized Quicksort shows more consistent performance across all input types.

---

## Part 2: Hashing with Chaining

### Implementation
- Implemented a hash table using chaining for collision handling.
- Each index stores a list of key-value pairs.
- Supported operations:
  - Insert
  - Search
  - Delete
- Implemented **dynamic resizing** when load factor exceeds 0.7.

### Analysis
- Average-case time complexity: **O(1 + α)**
- Worst-case time complexity: **O(n)**
- Load factor significantly impacts performance.
- Resizing helps maintain efficiency and reduce collisions.

---

## Files Included
- `Assignment.ipynb` → Jupyter Notebook with implementation and outputs
- `README.md` → Project documentation

---

## How to Run
1. Open the Jupyter Notebook (`.ipynb`) file.
2. Run all cells sequentially.
3. Observe outputs for:
   - Quicksort results
   - Performance comparison
   - Hash table operations

---

## Key Learnings
- Randomization can improve algorithm performance in unpredictable inputs.
- Algorithm efficiency depends not only on theory but also on input distribution.
- Hash tables require proper load factor management for optimal performance.
- Practical implementation helps reinforce theoretical concepts.

---

## Author
**Nischal Tiwari**  
University of the Cumberlands
