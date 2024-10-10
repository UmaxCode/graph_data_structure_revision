# Graph Data Structure

This repository contains implementations of various graph data structures and algorithms in Java. It serves as a reference for learning, revising, and applying graph-based problems.

## Table of Contents

- [Overview](#overview)
- [Graph Representation](#graph-representation)
- [Graph Algorithms](#graph-algorithms)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Graphs are a powerful data structure used to model relationships between objects. This repository covers key types of graph representations and algorithms, with clean and efficient implementations.

### Key Features:

- Adjacency List and Adjacency Matrix Representations
- Directed and Undirected Graphs
- Graph Traversal: Depth-First Search (DFS) and Breadth-First Search (BFS)
- Shortest Path Algorithms (Dijkstra's, Bellman-Ford)
- Topological Sort
- Minimum Spanning Tree (Prim's, Kruskal's)

## Graph Representation

### Adjacency List

An adjacency list is an array of lists. The size of the array is equal to the number of vertices. For each vertex, the list stores the neighbors of the vertex.

### Adjacency Matrix

An adjacency matrix is a 2D array of size `VxV`, where `V` is the number of vertices. An entry at position `(i, j)` indicates whether there is an edge from vertex `i` to vertex `j`.

## Graph Algorithms

- **Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking.
- **Breadth-First Search (BFS):** Explores all neighbors of a vertex before moving to the next level of neighbors.
- **Dijkstra's Algorithm:** Finds the shortest path between a starting node and all other nodes in a graph.
- **Kruskal's Algorithm:** Finds the minimum spanning tree by selecting edges with the lowest weights, ensuring no cycles.
- **Prim's Algorithm:** Builds the minimum spanning tree by adding the shortest edge to a growing subtree.
- **Topological Sort:** Orders vertices in a Directed Acyclic Graph (DAG) such that for every directed edge `u -> v`, `u` comes before `v`.
