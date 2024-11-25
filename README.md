# dsa-notes
This repository contains the notes of different data structures and important questions which would help in acing interview rounds.

DSA ke 14 patterns 😉
Arrays
Arrays are a fundamental data structure that store elements of the same type in a continuous block of memory. They're crucial in understanding more advanced data structures and algorithms.

Fixed size, defined at creation time.
Direct access to elements based on index.
Efficient when size of data is known in advance, but costly to resize.
Hash Maps, Tables
A hash table (or hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values.

Provides very fast O(1) lookup and insertion.
Keys are unique and used to compute a hash, which points to the storage location.
Hash collisions are resolved through various methods, like chaining and open addressing.
Pointers
Pointers are a fundamental concept in programming that hold the memory address of a value.

Allow for efficient handling of arrays and data structures.
Enable the creation and manipulation of complex data structures.
Used to create dynamic data structures that can grow or shrink during runtime.
Linked List
A linked list is a linear data structure where each element points to the next.

Elements are not stored at contiguous memory locations.
Efficient insertions and deletions at any place as compared to an array.
Utilized in implementation of stacks, queues, and graphs.
Sliding Window
Sliding window is an algorithmic paradigm that provides a solution for problems dealing with arrays or lists.

Used for finding ranges or intervals in data.
Useful for tracking a 'window' of information as it moves across the data.
Efficient for problems requiring checking all subarrays of a certain size.
Binary Search
Binary Search is an efficient algorithm for finding an item from a sorted list of items.

Works by repeatedly dividing the search interval in half.
The initial interval includes the entire list.
Time complexity of O(log N).
Recursion
Recursion is a method of solving problems where the solution depends on solutions to smaller instances of the same problem.

Breaks a problem down into smaller, more manageable parts.
Uses a function that calls itself during its execution.
Needs a base case to prevent infinite loops.
Backtracking
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally.

Solves a complex problem by breaking it down into simpler, smaller sub-problems.
Backtracks when it realizes the current solution cannot be continued into a complete one.
Used in many problems such as puzzles, game playing, and constraint satisfaction problems.
BFS, DFS
Breadth-first search (BFS) and depth-first search (DFS) are algorithms for traversing or searching tree or graph data structures.

BFS explores all vertices at the present depth before moving to vertices at the next depth level.
DFS goes as deep as possible down one path before backing up to the next one.
Both are used in path finding, cycle detection, and solving puzzles.
Dynamic Programming
Dynamic Programming is an algorithmic paradigm that solves a complex problem by breaking it into simpler subproblems and stores the results of subproblems to avoid computing the same results again.

Uses memoization to store results of subproblems.
Solves overlapping subproblems.
Commonly used for optimization problems.
Trees
A tree is a widely used abstract data type that simulates a hierarchical tree structure.

Non-linear data structure with a root and nodes.
Nodes are connected by edges.
Various types of trees are used in computer science like binary tree, B-tree, AVL tree, etc.
Graphs
A Graph is a non-linear data structure consisting of nodes and edges.

Nodes are sometimes referred to as vertices and edges are lines or arcs that connect any two nodes.
Graphs can be directed (edges have direction) or undirected.
Graph algorithms include DFS, BFS, Dijkstra's algorithm, etc.
Topological Sorting
Topological Sorting for a directed acyclic graph (DAG) is a linear ordering of vertices such that for every directed edge u, v, vertex u comes before v in the ordering.

Helps in scheduling tasks from the given dependencies among tasks.
Can only be performed on DAGs.
Many real-world problems, like dependency resolution, can be modeled as topological sorts.
Greedy Algorithms
Greedy algorithm is an algorithmic paradigm that follows the problem solving approach of making the locally optimal choice at each stage with the hope of finding a global optimum.

Used for optimization problems.
Makes the best choice at each decision point.
Problems must exhibit properties of matroids for greedy to work optimally.
Priority Queue
A priority queue is a special type of queue in which each element is associated with a priority and is served according to its priority.

Elements with higher priority are dequeued before elements with lower priority.
If elements with equal priorities exist, they are served according to their ordering in the queue.
Implemented using arrays, linked-lists, or heaps.
Tries
A Trie, also called digital tree and sometimes radix tree or prefix tree, is a kind of search tree—an ordered tree data structure that is used to store a dynamic set or associative array where the keys are usually strings.

Efficient information retrieval data structure.
Searches, insertions, and deletions are all in O(L) time, where L is the length of the key/word.
Used in spell checking, auto-complete features, and IP routing.
Additional Topics
Kadane’s algorithm
Kadane's algorithm is used to find the largest sum contiguous subarray within a one-dimensional numeric array.

It's an example of a dynamic programming algorithm.
Solves the maximum subarray problem in linear time, O(n).
Djikstra’s algorithm
Dijkstra’s algorithm is a popular search algorithm used to determine the shortest path between nodes in a graph.

It's a greedy algorithm that finds the path with the smallest total weight.
Widely used in network routing protocols.
AVL Trees
An AVL tree is a self-balancing binary search tree, and it was the first such data structure to be invented.

The heights of the two child subtrees of any node differ by at most one.
Look-up, insertion, and deletion all take O(log n) time in both the average and worst cases.
Useful in databases and file systems where fast look-up times are critical.
Sorting
Sorting refers to arranging data in a particular format, either ascending or descending.

Various sorting algorithms exist with different time complexities: bubble sort (O(n^2)), quick sort (O(n log n)), merge sort (O(n log n)), etc.
Choice of sorting algorithm depends on specific requirements of the problem.
