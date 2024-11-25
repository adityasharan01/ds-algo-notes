# dsa-notes
This repository contains the notes of different data structures and important questions which would help in acing interview rounds.

# DSA ke 14 Patterns 😉

## Arrays
Arrays are a fundamental data structure that store elements of the same type in a continuous block of memory. They're crucial in understanding more advanced data structures and algorithms.

- Fixed size, defined at creation time.
- Direct access to elements based on index.
- Efficient when the size of data is known in advance but costly to resize.

## Hash Maps, Tables
A hash table (or hash map) is a data structure that implements an associative array abstract data type, mapping keys to values.

- Provides very fast O(1) lookup and insertion.
- Keys are unique and used to compute a hash, which points to the storage location.
- Hash collisions are resolved through methods like chaining and open addressing.

## Pointers
Pointers are a fundamental concept in programming that hold the memory address of a value.

- Allow efficient handling of arrays and data structures.
- Enable the creation and manipulation of complex data structures.
- Used to create dynamic data structures that can grow or shrink during runtime.

## Linked List
A linked list is a linear data structure where each element points to the next.

- Elements are not stored at contiguous memory locations.
- Efficient insertions and deletions compared to arrays.
- Utilized in the implementation of stacks, queues, and graphs.

## Sliding Window
Sliding window is an algorithmic paradigm that provides a solution for problems dealing with arrays or lists.

- Used for finding ranges or intervals in data.
- Useful for tracking a 'window' of information as it moves across the data.
- Efficient for problems requiring checking all subarrays of a certain size.

## Binary Search
Binary Search is an efficient algorithm for finding an item from a sorted list of items.

- Works by repeatedly dividing the search interval in half.
- The initial interval includes the entire list.
- Time complexity of O(log N).

## Recursion
Recursion is a method of solving problems where the solution depends on solutions to smaller instances of the same problem.

- Breaks a problem down into smaller, manageable parts.
- Uses a function that calls itself during its execution.
- Needs a base case to prevent infinite loops.

## Backtracking
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally.

- Solves a complex problem by breaking it down into simpler sub-problems.
- Backtracks when the current solution cannot be completed.
- Used in puzzles, game playing, and constraint satisfaction problems.

## BFS, DFS
Breadth-first search (BFS) and depth-first search (DFS) are algorithms for traversing or searching tree or graph data structures.

- BFS explores all vertices at the current depth before moving to the next.
- DFS goes as deep as possible down one path before backtracking.
- Used in pathfinding, cycle detection, and solving puzzles.

## Dynamic Programming
Dynamic Programming is an algorithmic paradigm that solves a complex problem by breaking it into simpler subproblems and storing results.

- Uses memoization to avoid redundant computations.
- Solves overlapping subproblems.
- Commonly used for optimization problems.

## Trees
A tree is a widely used abstract data type that simulates a hierarchical tree structure.

- Non-linear data structure with a root and nodes.
- Nodes are connected by edges.
- Includes various types like binary trees, AVL trees, and B-trees.

## Graphs
A graph is a non-linear data structure consisting of nodes and edges.

- Nodes (vertices) are connected by edges (lines or arcs).
- Can be directed (edges have direction) or undirected.
- Includes algorithms like DFS, BFS, and Dijkstra's.

## Topological Sorting
Topological Sorting for a directed acyclic graph (DAG) is a linear ordering of vertices.

- Ensures for every directed edge u → v, u appears before v.
- Applicable only for DAGs.
- Models real-world problems like task scheduling and dependency resolution.

## Greedy Algorithms
Greedy algorithm is an algorithmic paradigm that makes the locally optimal choice at each stage.

- Used for optimization problems.
- Makes the best choice at each decision point.
- Works well when problems exhibit properties of matroids.

## Priority Queue
A priority queue is a special type of queue where elements are served according to their priority.

- Higher-priority elements are dequeued before lower-priority ones.
- Equal-priority elements are served based on order in the queue.
- Implemented using arrays, linked lists, or heaps.

## Tries
A Trie is an ordered tree data structure used for storing strings.

- Efficient information retrieval data structure.
- Searches, insertions, and deletions are all O(L) time, where L is the string length.
- Used in spell checking, autocomplete, and IP routing.

---

### Additional Topics

#### Kadane’s Algorithm
Kadane's algorithm finds the largest sum contiguous subarray in a one-dimensional numeric array.

- Example of a dynamic programming algorithm.
- Solves the maximum subarray problem in O(n) time.

#### Dijkstra’s Algorithm
Dijkstra's algorithm determines the shortest path between nodes in a graph.

- A greedy algorithm that minimizes total path weight.
- Widely used in network routing protocols.

#### AVL Trees
AVL tree is a self-balancing binary search tree.

- The height difference of child subtrees is at most one.
- Look-up, insertion, and deletion take O(log n) time.
- Useful in databases and file systems for fast look-up.

#### Sorting
Sorting arranges data in ascending or descending order.

- Algorithms include bubble sort (O(n²)), quicksort (O(n log n)), and mergesort (O(n log n)).
- Choice of sorting algorithm depends on specific problem requirements.
