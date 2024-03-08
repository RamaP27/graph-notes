# Graph Notes

This is for my learning purpose. 
Depth-First Search (DFS) is a graph traversal algorithm that explores as far as possible along each branch before backtracking. It uses a stack to keep track of visited vertices and backtracks when necessary.

Breadth-First Search (BFS) is a graph traversal algorithm that explores all vertices at the current depth before moving to the next level. It uses a queue to keep track of visited vertices and ensures that closer vertices are explored first.

## [Graphs 1](https://github.com/umarf2212/graph-notes/blob/main/Graphs%201.pdf)

- Graph Representation
- Types of Graphs
- DFS and BFS
- Connected Components

## [Graphs 2](https://github.com/umarf2212/graph-notes/blob/main/Graphs%202.pdf)

- Q. Shortest distance b/w S and D with some cells blocked
  - BFS basics on Matrix
- Q. Shortest distance from Residences to Hospitals
  - Multiisource BFS
- Q. Cycle in Undirected Graph
  - By keeping track of parent node and checking if revisited
  - By counting no. of edges and vertices in each CC
    - if E > V-1 => cycle is present
- Q. Cycle in Directed Graph

## [Graphs 3](https://github.com/umarf2212/graph-notes/blob/main/Graphs%203.pdf)

- Q. Capture land which is completely surrounded
- Q. Find order to perform N dependent jobs
- **Topological Sort**
- **Bipartite Graphs**
- **Graph Coloring**

## [Graphs 4](https://github.com/umarf2212/graph-notes/blob/main/Graphs%204.pdf)

- Q. Find min distance from source to all other nodes in unweighted graph
- Q. Same as above, but weights are in the range [1, 2, 3]
- Single source shortest path - **Dijkstra's Algorithm**
- All pair shortest path - **Floyd Warshall Algorithm**
- Q. Given a N*N chessboard and K knights placed in it. If a knight is reachable from other Knight in 1 step, you may swap them. Find the number of ways of arranging them.

## [Graphs 5](https://github.com/umarf2212/graph-notes/blob/main/Graphs%205.pdf)

- Q. You are a delivery person. Given N houses (all connected), can you remove some roads such that it's still possible to deliver to all the houses (you can remove as many edges as possible).
- **Spanning Trees**
- **Minimum Spanning Tree**
- **Prim's Algorithm**
- **Disjoint Set Union (DSU Data Structure)**
  - Optimisation and Path Compression
  - Find if given Graph is connected
  - Find # of CC in Unidrected Graph
  - Check if there's a cycle in Undirected Graph
- **Kruskal's Algorithm**
