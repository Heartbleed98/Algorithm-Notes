# Algorithm List

This repository contains implementations and explanations of the following algorithms:

## 1. Search Algorithms

### Binary Search
- **File**: `Search/BinarySearch.cpp`
- **Time Complexity**: O(log n)
- **Description**: Efficient algorithm for finding a specific element in a sorted array

### Interpolation Search
- **File**: `Search/InterpolationSearch.cpp`
- **Time Complexity**: O(log log n) average case
- **Description**: Improved search algorithm based on numerical distribution

## 2. Sort Algorithms

### Quick Sort
- **Files**: `Sort/QuickSort1.cpp`, `Sort/QuickSort2.cpp`
- **Time Complexity**: O(n log n) average case, O(n²) worst case
- **Description**: Efficient divide-and-conquer sorting algorithm

### Heap Sort
- **File**: `Sort/HeapSort.cpp`
- **Time Complexity**: O(n log n)
- **Description**: Sorting using heap data structure

### Insertion Sort
- **File**: `Sort/InsertionSort.cpp`
- **Time Complexity**: O(n²)
- **Description**: Sorts by inserting elements one by one into sorted sequence

### Binary Insertion Sort
- **File**: `Sort/BInsertionSort.cpp`
- **Time Complexity**: O(n²)
- **Description**: Insertion sort optimized with binary search

### Selection Sort
- **File**: `Sort/SelectionSort.cpp`
- **Time Complexity**: O(n²)
- **Description**: Sorts by repeatedly selecting the minimum element

## 3. Tree Algorithms

### Morris Post-order Traversal
- **File**: `Tree/MorrisPosorder.cpp`
- **Space Complexity**: O(1)
- **Description**: Binary tree post-order traversal without extra stack space

### Trie (Prefix Tree)
- **File**: `Tree/Trie.cpp`
- **Description**: Tree data structure for string collections

### Binary Tree Diameter
- **File**: `Tree/二叉树的直径.cpp`
- **Description**: Calculates the longest path between any two nodes in a binary tree

### Lowest Common Ancestor (LCA)
- **File**: `Tree/最近公共祖先.cpp`
- **Description**: Finds the nearest common ancestor of two nodes in a tree

### Binary Tree Node Ancestors
- **File**: `Tree/二叉树节点的祖先.cpp`
- **Description**: Finds all ancestors of a given node in a binary tree

## 4. Graph Algorithms

### Breadth-First Search (BFS)
- **File**: `Graph/BFS.cpp`
- **Time Complexity**: O(V + E)
- **Description**: Layer-by-layer graph traversal algorithm

### Depth-First Search (DFS)
- **File**: `Graph/DFS.cpp`
- **Time Complexity**: O(V + E)
- **Description**: Deep graph traversal algorithm

### Dijkstra's Shortest Path Algorithm
- **File**: `Graph/Dijkstra.cpp`
- **Time Complexity**: O(V²) or O((V + E) log V) with priority queue
- **Description**: Greedy algorithm for single-source shortest path

### Topological Sorting
- **File**: `Graph/Topological Sorting.cpp`
- **Time Complexity**: O(V + E)
- **Description**: Linear ordering of directed acyclic graph

## 5. String Algorithms

### Sunday String Matching Algorithm
- **File**: `String/sunday.cpp`
- **Time Complexity**: O(mn) worst case, O(n) average case
- **Description**: Efficient string pattern matching algorithm

## 6. Other Algorithms

### Manacher's Algorithm
- **File**: `Others/Manacher.cpp`
- **Time Complexity**: O(n)
- **Description**: Linear time algorithm to find all palindromic substrings

### Sieve of Eratosthenes
- **File**: `Others/EratosthenesSieve.cpp`
- **Time Complexity**: O(n log log n)
- **Description**: Efficient algorithm for finding prime numbers

### Euler's Sieve
- **File**: `Others/EulerSieve.cpp`
- **Time Complexity**: O(n)
- **Description**: Linear time prime sieving algorithm

### Union-Find (Disjoint Set Union)
- **File**: `Others/并查集.cpp`
- **Time Complexity**: O(α(n)) with path compression and union by rank
- **Description**: Data structure for maintaining disjoint sets

### Full Permutation
- **Files**: `Others/FullPermutation_1.cpp`, `Others/FullPermutation_2.cpp`
- **Time Complexity**: O(n!)
- **Description**: Algorithms to generate all possible permutations

### Integer Reverse
- **File**: `Others/整数反转.cpp`
- **Description**: Algorithm to reverse the digits of an integer

### Longest Common Prefix
- **File**: `Others/最长公共前缀.cpp`
- **Description**: Finds the longest common prefix among an array of strings

## Algorithm Statistics

- **Search Algorithms**: 2 types
- **Sort Algorithms**: 5 types
- **Tree Algorithms**: 5 types
- **Graph Algorithms**: 4 types
- **String Algorithms**: 1 type
- **Other Algorithms**: 9 types

**Total**: 26 algorithm implementations

## Complexity Distribution

### Time Complexity
- **O(1)**: Constant time algorithms
- **O(log n)**: Logarithmic time algorithms (Binary Search, etc.)
- **O(n)**: Linear time algorithms (Manacher, Euler's Sieve, etc.)
- **O(n log n)**: Linearithmic time algorithms (Quick Sort, Heap Sort, etc.)
- **O(n²)**: Quadratic time algorithms (Insertion Sort, Selection Sort, etc.)
- **O(V + E)**: Graph algorithm complexity (BFS, DFS, Topological Sort)

### Application Areas
- **Data Structure Operations**: Trees, Graphs, Union-Find
- **String Processing**: Pattern matching, palindrome detection
- **Mathematical Computation**: Prime sieving, numerical processing
- **Algorithm Design**: Divide-and-conquer, greedy algorithms, dynamic programming concepts

This repository provides complete C++ implementation examples for learning and understanding various classic algorithms.