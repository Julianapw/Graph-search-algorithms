# Graph Search Algorithms: Breadth-First Search (BFS) vs Depth-First Search (DFS)

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Collections](https://img.shields.io/badge/Python-Collections%20Deque-lightgrey?style=flat-square&logo=python)
![Recursion](https://img.shields.io/badge/Algorithm-Recursion-lightgrey?style=flat-square)

## Overview
This repository presents the implementation and analysis of two classical **graph search algorithms**: **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**.

The project explores how both algorithms traverse a **state-space graph** to determine the best path from an **initial node (A)** to a **goal node (H)**. It includes the construction of a graph representation using Python dictionaries and compares the behavior and results of each search strategy.

This practice demonstrates fundamental concepts of **Artificial Intelligence search techniques** and **graph traversal strategies**.

---

## Objectives & Requirements

- Construct the **tree representation** of the given graph
- Identify the best path from node **A to H**
- Perform manual analysis using:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
- Implement the graph using a **Python dictionary structure**
- Develop Python implementations for:
  - BFS algorithm
  - DFS algorithm
- Compare results obtained by both strategies

---

## Key Features

### Graph Representation
Implementation of the environment using a **dictionary-based graph structure** in Python.

### Breadth-First Search (BFS)
Explores nodes **level by level**, ensuring the shortest path is found in terms of number of edges.

### Depth-First Search (DFS)
Explores nodes **deeply before backtracking**, prioritizing depth over breadth.

### Path Discovery
Both algorithms return the path from the **initial node (A)** to the **goal node (H)**.

### Strategy Comparison
Analysis of differences between BFS and DFS based on:

- search behavior
- path optimality
- traversal order
- computational characteristics

---

## Algorithms Implemented

### Breadth-First Search (BFS)

Characteristics:

- Uses a **queue (FIFO)**
- Guarantees shortest path in unweighted graphs
- Explores neighbors first before going deeper

### Depth-First Search (DFS)

Characteristics:

- Uses a **stack (LIFO)** or recursion
- Explores deepest nodes first
- May not guarantee shortest path
