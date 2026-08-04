# Atlas - Day 11

**Date:** 04 August 2026

---

# 📚 Topics Covered

## Graphs - Foundations

Started the Graphs section and learned the fundamental traversal techniques.

### Concepts Learned
- Graph representation in grids
- Depth First Search (DFS)
- Breadth First Search (BFS)
- Connected Components
- Grid Traversal
- Multi-Source BFS
- Shortest distance in an unweighted graph
- Level-order BFS
- Visited marking techniques

---

# ✅ Problems Solved

## LC 200 : Number of Islands
- DFS
- Connected Components
- Grid Traversal

### Learned
- Every island is a connected component.
- DFS can completely traverse one component before moving to the next.
- Marking visited cells in-place avoids using an extra visited array.

---

## LC 994 : Rotting Oranges
- Multi-Source BFS
- Level Order Traversal

### Learned
- Initialize the queue with every rotten orange.
- All rotten oranges spread simultaneously.
- Each BFS level represents one minute.
- `for _ in range(len(queue))` processes exactly one minute at a time.

---

## LC 695 : Max Area of Island
- DFS
- Flood Fill

### Learned
- DFS can return information instead of only visiting nodes.
- The recursive calls can accumulate the size of an island.
- Maintain the maximum area while traversing every connected component.

---

## LC 286 : Walls and Gates
- Multi-Source BFS
- Shortest Distance

### Learned
- Start BFS from every gate instead of every empty room.
- The first time a room is visited is always its minimum distance from any gate.
- Multi-source BFS efficiently computes shortest distances from multiple sources simultaneously.

---

# 💡 Key Takeaways

- A 2D grid can be treated as a graph.
- DFS is ideal for exploring complete connected components.
- BFS naturally computes shortest paths in unweighted graphs.
- Multi-Source BFS is useful whenever multiple starting points expand simultaneously.
- Mark nodes as visited immediately when processing them to avoid duplicate work.
- Many matrix problems are actually graph traversal problems.

---

# 📈 Progress

### Topic
- ✅ Graph Foundations Started

### Problems Completed Today
- LC 200 — Number of Islands
- LC 994 — Rotting Oranges
- LC 695 — Max Area of Island
- LC 286 — Walls and Gates

**Problems Solved Today:** 4
