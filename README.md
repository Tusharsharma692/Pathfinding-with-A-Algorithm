# A\* Pathfinding Algorithm

## Problem Statement

The **A**\* pathfinding algorithm\*\* is designed to find the shortest path in a **2D grid (matrix)** from a given **start position** to a **goal position**, while avoiding obstacles. The grid consists of:

- `0` representing an **open cell**, meaning movement is allowed.
- `1` representing an **obstacle**, meaning movement is not allowed.
- A defined **start position**, which is the initial point of the search.
- A defined **goal position**, which is the target destination.
- Movement is allowed **only in four directions**: **up, down, left, and right** (no diagonal movement).

### **Objective**

The goal of the algorithm is to find the **shortest path** from the start position to the goal position in the grid. The algorithm ensures that the path avoids obstacles and reaches the goal efficiently using a heuristic-based approach.

### **Example Grid Representation**

```
S  1  0  0  0
0  1  0  1  G
0  0  0  1  0
0  1  1  1  0
0  0  0  0  0
```

- `S` = Start position (e.g., `(0,0)`, top-left corner)
- G = Goal position (e.g., (1,4), top-right corner)
- `1` = Obstacles (impassable cells)
- `0` = Open path (passable cells)

The algorithm will calculate the optimal route from `S` to `G` while avoiding obstacles and minimizing the total path cost.

---

This problem is commonly used in AI, robotics, and game development for **pathfinding and navigation** applications.



