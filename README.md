# Red-Black Tree Project

## Overview
A **Red-Black Tree** is a self-balancing binary search tree where each node has an additional color attribute (red or black). It ensures balanced tree structure, maintaining operations like **insertion**, **deletion**, and **search** in **O(log n)** time. This project demonstrates the implementation and operations of a Red-Black Tree.

---

## Key Features
- **Self-Balancing**: Ensures the tree remains balanced after insertions and deletions.
- **Efficient Operations**: Guarantees **O(log n)** time complexity for insert, delete, and search.
- **Applications**:
  - Used in C++ STL (`map`, `multiset`, `multimap`).
  - Implemented in Java (`TreeMap`, `TreeSet`).
  - Applied in CPU scheduling (Linux Completely Fair Scheduler).
  - Used in MySQL for table indexing.

---

## Red-Black Tree Properties
1. Every node is either **red** or **black**.
2. The **root** is always black.
3. No two red nodes are adjacent (no red parent-red child).
4. Every path from a node to its descendant `NULL` nodes has the same number of black nodes.
5. All leaf (`NULL`) nodes are black.

---

## Operations
### Insertion
1. Insert a new node as a red leaf.
2. Rebalance the tree by performing **rotations** and **recoloring** if necessary.
3. Ensure all Red-Black Tree properties are maintained.

### Deletion
1. Perform standard BST deletion.
2. Replace the deleted node with its successor/predecessor.
3. Rebalance the tree by performing **rotations** and **recoloring** if necessary.
4. Ensure all Red-Black Tree properties are maintained.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Red-Black-Tree.git
