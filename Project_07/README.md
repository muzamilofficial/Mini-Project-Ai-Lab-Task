## 🧠 Overview
This project implements the **A\* (A-Star) Search Algorithm**, an advanced pathfinding and graph traversal technique widely used in **Artificial Intelligence**, **Robotics**, and **Game Development**.  
It finds the **shortest path** between a start node and a goal node using both **actual cost** (g) and **heuristic cost** (h).

---

## ⚙️ How It Works
- The algorithm keeps two sets of nodes:
  - **Open List** → Nodes to be explored  
  - **Closed List** → Nodes already visited  
- For each node:
  - It calculates the total cost:  
    ```
    f(n) = g(n) + h(n)
    ```
    where  
    - `g(n)` = actual distance from the start node  
    - `h(n)` = heuristic estimate to the goal node
- The algorithm always expands the node with the smallest `f(n)` value.
- When the goal node is reached, the optimal path is reconstructed.

---

## Requirements
- Python 3.x

---

## Concepts Used
- Graph traversal
- Heuristic search (A* Algorithm)
- Pathfinding optimization
- Artificial Intelligence fundamentals


