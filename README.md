# Data Structures and Algorithms (DSA) Patterns and Algorithm Selection Guide

This guide provides an overview of common algorithm patterns and their appropriate use cases across different data structures. Use this as a reference to identify the right algorithmic approach for solving various DSA problems.

## Table of Contents

1. [Array](#array)
2. [Sliding Window](#sliding-window)
3. [Stack](#stack)
4. [Hash Table](#hash-table)
5. [Linked List](#linked-list)
6. [Tree](#tree)
7. [Graph](#graph)
8. [Heap/Priority Queue](#heappriority-queue)
9. [Queue/Deque](#queuedeque)
10. [Trie](#trie)
11. [Dynamic Programming (DP)](#dynamic-programming-dp)

## Array

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Searching in a sorted array               | Binary Search                            | Find element in sorted array, Rotated array search |
| Finding duplicates                        | Hashing, Sorting and Two Pointers        | Find duplicates, Contains duplicate II             |
| Subarray with given sum                   | Sliding Window                           | Longest subarray with sum k, Subarray sum equals k |
| Sorting                                   | Merge Sort, Quick Sort                   | Sorting integers, Sorting strings                  |
| Rearranging elements                      | Two Pointers, In-place operations        | Move zeros, Sort colors                            |


## Sliding Window

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Longest substring without repeating characters | Sliding Window + Hash Map            | Longest substring without repeating characters     |
| Maximum sum subarray                      | Sliding Window                           | Maximum sum subarray of size k                     |
| Minimum window substring                  | Sliding Window + Two Pointers            | Minimum window substring, Smallest subarray        |
| Subarrays with product less than k        | Sliding Window + Two Pointers            | Subarrays with product less than k                 |


## Stack

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Balancing parentheses                     | Stack                                    | Valid parentheses, Remove invalid parentheses      |
| Evaluate postfix/prefix expressions       | Stack                                    | Evaluate reverse Polish notation                   |
| Implement queue using stacks              | Two Stacks                               | Implement queue using stacks                       |
| Next Greater Element                      | Monotonic Stack                          | Next greater element I/II                          |
| Stock span problem                        | Monotonic Stack                          | Stock span problem                                 |


## Queue/Deque

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Sliding window maximum                    | Deque                                    | Sliding window maximum                             |
| Level order traversal of tree             | BFS using Queue                          | Binary tree level order traversal                  |
| Implement stack using queues              | Two Queues                               | Implement stack using queues                       |
| First non-repeating character in stream   | Queue                                    | First unique character in a string                 |

## Hash Table

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Finding duplicates                        | Hash Map                                 | Two sum, Contains duplicate                        |
| Grouping anagrams                         | Hash Map                                 | Group anagrams, Count characters                   |
| Frequency counting                        | Hash Map                                 | Top k frequent elements, Word frequency            |
| LRU Cache implementation                  | Hash Map + Doubly Linked List            | LRU cache                                          |
| Subarray with sum k                       | Hash Map, Prefix Sum                     | Subarray sum equals k, Longest subarray with sum k |

## Linked List

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Reversal of list                          | In-Place Reversal                        | Reverse linked list, Reverse nodes in k-group      |
| Detect cycle                              | Fast and Slow Pointers                   | Detect cycle in linked list                        |
| Merge two sorted lists                    | Two Pointers                             | Merge two sorted lists                             |
| Finding middle of list                    | Fast and Slow Pointers                   | Find middle node of linked list                    |
| Removing nth node from end                | Two Pointers                             | Remove nth node from end of list                   |

## Tree

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Tree Traversals (Preorder, Inorder, Postorder) | Recursive or Iterative Traversal     | Binary tree traversal, N-ary tree traversal        |
| Level-order traversal                     | Breadth-First Search (BFS)               | Binary tree level order traversal                  |
| Validate Binary Search Tree (BST)         | Inorder Traversal, Recursion             | Validate BST, Convert BST to sorted list           |
| Lowest Common Ancestor                    | DFS, Recursion                           | Lowest common ancestor of a binary tree            |
| Path sum problems                         | DFS, Backtracking                        | Path sum, Binary tree maximum path sum             |
| Balancing trees                           | Recursion, Height Calculation            | Check if balanced, Balanced BST from sorted array  |

## Graph

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Traversal of graph nodes                  | Depth-First Search (DFS), BFS            | Connected components, DFS of a graph               |
| Shortest path in unweighted graph         | BFS                                      | Shortest path in unweighted graph                  |
| Shortest path in weighted graph           | Dijkstra's Algorithm                     | Shortest path in weighted graph                    |
| Cycle detection                           | DFS, Union-Find                          | Detect cycle in directed/undirected graph          |
| Topological sorting                       | DFS, Kahn's Algorithm                    | Course schedule, Task scheduling                   |
| Finding connected components              | BFS, DFS                                 | Number of islands, Connected components            |

## Heap/Priority Queue

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Find kth smallest/largest element         | Min-Heap, Max-Heap                       | Kth largest element, Median from data stream       |
| Merge k sorted lists                      | Min-Heap                                 | Merge k sorted lists                               |
| Task scheduling with deadlines            | Greedy, Max-Heap                         | Task scheduler, Course schedule II                 |


## Trie

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Prefix search                             | Trie (Prefix Tree)                       | Implement Trie, Word search II                     |
| Auto-complete                             | Trie                                     | Design search autocomplete system                  |
| Word search problems                      | Trie + DFS                               | Word search II, Longest word in dictionary         |

## Dynamic Programming (DP)

| **Problem Type**                          | **Algorithm/Pattern**          | **Example Problems**                               |
|-------------------------------------------|------------------------------------------|----------------------------------------------------|
| Fibonacci-like sequence, Counting paths   | DP with memoization                      | Climbing stairs, House robber                      |
| Subset problems                           | DP with subset sum                       | Subset sum, Partition equal subset sum             |
| Longest increasing subsequence            | DP with binary search                    | Longest increasing subsequence, Maximum sum        |
| Knapsack problem                          | DP with space optimization               | 0/1 Knapsack, Unbounded knapsack                   |


## Contributing

If you'd like to contribute to this guide, feel free to submit a pull request with additional patterns, algorithms, or example problems.

## License

This guide is open-sourced under the MIT License. Feel free to use and distribute it as needed.
