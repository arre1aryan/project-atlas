# Atlas - Day 12

**Date:** 05 August 2026

---

# 📚 Topics Covered

## Graphs - Traversal & Connectivity

Continued the Graphs section and worked on graph cloning, connected components, cycle detection, boundary-based traversal, and graph-based state exploration.

### Concepts Learned
- Graph representation using adjacency lists
- Depth First Search (DFS)
- Breadth First Search (BFS)
- Connected Components
- Cycle Detection in Undirected Graphs
- Parent Tracking
- Graph Cloning
- Boundary-based Traversal
- Multi-Source Traversal
- Reverse Graph Traversal
- State-based Graph Problems

---

# ✅ Problems Solved

## LC 133 : Clone Graph
- DFS
- Graph Traversal
- Hash Map / Visited Mapping

### Learned
- Maintain a mapping between original nodes and their cloned counterparts.
- Clone each node only once.
- The mapping also prevents infinite recursion when cycles exist in the graph.

---

## LC 130 : Surrounded Regions
- DFS
- Boundary Traversal
- Connected Components

### Learned
- Instead of searching for surrounded regions directly, start from boundary `O` cells.
- Any `O` connected to the boundary cannot be surrounded.
- Mark safe regions first and convert the remaining `O` cells to `X`.

---

## LC 323 : Number of Connected Components in an Undirected Graph
- DFS
- Connected Components
- Adjacency List

### Learned
- Every DFS started from an unvisited node explores exactly one connected component.
- Count how many times a new DFS needs to be started.
- Graph representation using an adjacency list is efficient for sparse graphs.

---

## LC 261 : Graph Valid Tree
- DFS
- Cycle Detection
- Connected Components
- Parent Tracking

### Learned
- A valid tree must be **connected and acyclic**.
- If a visited neighbor is not the parent, a cycle exists.

---

## LC 417 : Pacific Atlantic Water Flow
- DFS / BFS
- Boundary Traversal
- Reverse Graph Thinking

### Learned
- Instead of checking where water can flow from every cell, start from the oceans and move inward.
- Reverse thinking can transform an expensive traversal into an efficient one.

---

## LC 202 : Happy Number
- Cycle Detection
- Hash Set
- State Traversal


---

# 💡 Key Takeaways

- Graphs are not limited to explicit node-edge structures; many problems can be modeled as graphs of states or grid cells.
- DFS and BFS are reusable patterns that appear across many different-looking problems.
- Connected component problems can often be solved by counting DFS/BFS traversals from unvisited nodes.
- For undirected cycle detection, **parent tracking** is essential.
- Boundary traversal is a powerful technique for problems where the boundary determines whether a region is safe.
- Reverse traversal can make problems like Pacific Atlantic Water Flow much simpler.
- Cycle detection is a general technique that also applies to problems involving sequences of states.

---

# 📈 Progress

### Topic
- 🟡 Graphs In Progress

### Problems Completed Today
- LC 133 — Clone Graph
- LC 130 — Surrounded Regions
- LC 323 — Number of Connected Components in an Undirected Graph
- LC 261 — Graph Valid Tree
- LC 417 — Pacific Atlantic Water Flow
- LC 202 — Happy Number

**Problems Solved Today:** 6