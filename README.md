
# Comparative Analysis of Informed and Uninformed Search Algorithms 🔍🧭

This project explores and compares the performance of fundamental search algorithms in AI by simulating a pathfinding task in a grid-based environment.

## 📌 Assignment Information
- **Course:** Artificial Intelligence
- **Assignment:** #2
- **Title:** The Quest For A Treasure
- **Student:** Muhammad Azan Afzal
- **Roll Number:** 22I-1741
- **Date Submitted:** March 9, 2025

---

## 📚 Overview

The assignment involves implementing and analyzing five pathfinding algorithms:

- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)
- Greedy Best-First Search (GBFS)
- A* Search

The algorithms are tested on a 10x10 grid with various terrain types such as walls, portals, quicksand, and beast zones.

---

## 🧠 Algorithms Summary

### 🔵 BFS (Breadth-First Search)
- **Type:** Uninformed
- **Strength:** Finds shortest path (in steps)
- **Weakness:** Ignores terrain cost, high memory usage

### 🔵 DFS (Depth-First Search)
- **Type:** Uninformed
- **Strength:** Fast and low memory
- **Weakness:** May find suboptimal paths

### 🟡 UCS (Uniform Cost Search)
- **Type:** Informed
- **Strength:** Guarantees lowest cost path
- **Weakness:** Slow, high memory usage

### 🟢 GBFS (Greedy Best-First Search)
- **Type:** Informed
- **Strength:** Fastest and most memory-efficient
- **Weakness:** Does not guarantee optimality

### 🟢 A* Search
- **Type:** Informed
- **Strength:** Balances cost and heuristic for optimal path
- **Weakness:** Not the fastest or lightest on memory

---

## 📊 Performance Comparison

| Algorithm | Execution Time | Memory Usage | Optimality |
|-----------|----------------|--------------|------------|
| BFS       | 0.005748 sec   | 8368 bytes   | ✔ Shortest steps |
| DFS       | 0.001002 sec   | 7400 bytes   | ✘ Suboptimal |
| UCS       | 0.004238 sec   | 11768 bytes  | ✔ Cost-optimal |
| GBFS      | 0.000329 sec   | 1904 bytes   | ✘ Suboptimal |
| A*        | 0.001616 sec   | 5728 bytes   | ✔ Cost-optimal ✅ Most Efficient |

---

## 🏁 Conclusion

- **Most Efficient:** `A* Search`
  - Balances speed, memory usage, and optimality.
- **Fastest:** `Greedy Best-First Search (GBFS)`
- **Best for Cost-Optimal Path:** `UCS` and `A*`
- **Best for Memory Constraints:** `GBFS` and `DFS`

---

## 🛠️ How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the .ipynb file
---

## 🧑‍💻 Author

- **Muhammad Azan Afzal**  
- **Roll No:** 22I-1741  
- **University:** FAST NUCES Islamabad
