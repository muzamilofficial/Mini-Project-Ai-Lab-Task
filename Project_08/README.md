# Minimax Algorithm (Game Tree Evaluation)

---

## 🧠 Overview
This project demonstrates the **Minimax Algorithm**, a key concept in **Artificial Intelligence** used for **decision-making** in games.  
It is a recursive algorithm that simulates all possible moves and chooses the optimal outcome for a player assuming the opponent also plays optimally.

---

## ⚙️ How It Works
- The algorithm explores a **binary game tree** recursively.
- Two players alternate turns:
  - **Maximizer** tries to get the maximum score.
  - **Minimizer** tries to minimize the score.
- The recursion continues until the **target depth (leaf node)** is reached.
- The algorithm then backtracks and evaluates the best move for each level.

---

## 🧩 Algorithm Logic

| Step | Description |
|------|--------------|
| 1️⃣ | Define a recursive `minimax()` function that takes depth, node index, player turn, scores, and target depth. |
| 2️⃣ | If current depth equals the target depth → return the score at that node. |
| 3️⃣ | If it's the **maximizer's turn**, return the **maximum** of two child nodes. |
| 4️⃣ | If it's the **minimizer's turn**, return the **minimum** of two child nodes. |
| 5️⃣ | Continue recursion until the best value is found at the root node. |

--

## Requirements
-  Python 3.x
-  math module (built-in)

---


