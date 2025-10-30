## Overview
This project demonstrates the implementation of the **Depth-First Search (DFS)** algorithm in Python using **recursion** and **stack-based traversal**.  
DFS is a graph traversal algorithm that explores as far as possible along each branch before backtracking.

---

## Features
- Uses recursion to explore each node  
- Tracks visited nodes  
- Stores traversal order in a stack  
- Displays traversal from a start node to a goal node  

---

## How It Works
1. The class `DFS` initializes two lists:
   - `visited` → keeps track of visited nodes  
   - `stack` → acts as a call stack for traversal  
2. The `push()` method:
   - Marks the current node as visited and pushes it to the stack.  
   - Prints the current traversal path.  
   - Recursively visits all child nodes of the current node until the goal is found.  

---

## Requirements

- Python 3.x
