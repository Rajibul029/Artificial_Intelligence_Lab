# Artificial Intelligence Laboratory Experiments:
https://github.com/Rajibul029/Artificial_Intelligence_Lab

A weekly running log of all Artificial Intelligence Lab Exp.

---

### 📍 Week 1: Introduction to Python Libraries for AI

* **Core Implementations:**
  * **NumPy & Pandas:** Formatted structural databases and calculated essential array metrics (Sum, Mean, Max).
  * **Matplotlib:** Plotted static data visualizations using a Student Marks bar chart layout.
  * **Scikit-Learn:** Preprocessed text data by transforming categorical student strings into numerical digits.
  * **TensorFlow & OpenCV:** Evaluated math matrices and generated basic coordinate shapes on a digital raw canvas.

---

### 📍 Week 2: Graph Traversal Algorithms (BFS & DFS)

* **Core Implementations:**
  * **NetworkX:** Structured a node matrix layout (`add_edges_from`) to map out graph nodes and visual coordinate connections.
  * **Matplotlib:** Rendered dynamic color configurations to map traversed routes and generated interactive animation sequences (`FuncAnimation`).
  * **Breadth-First Search (BFS):** Deployed a FIFO matrix mapping strategy (`queue.popleft()`) to explore layers level-by-layer across connected neighbors.
  * **Depth-First Search (DFS):** Programmed a LIFO structural branch layout (`stack.pop()`) to traverse deep structural vectors before backtracking.

---

### 📍 Week 3: Uniform Cost Search (UCS)

* **Core Implementations:**
  * **NetworkX:** Built a weighted graph using adjacency lists and visualized nodes, edges, and edge weights with a custom layout.
  * **Matplotlib:** Developed an interactive visualization that dynamically updates node colors, explored paths, and cumulative path costs during execution.
  * **Priority Queue (Heap):** Implemented a min-priority queue using Python's heapq to always expand the node with the lowest accumulated path cost.
  * **Uniform Cost Search (UCS):** Designed a cost-based graph traversal algorithm that computes the optimal (minimum-cost) path by maintaining cumulative costs (g(n)) and updating the frontier until the goal node is reached.

---

### 📍 Week 4: A* Search Algorithm

* **Core Implementations:**
  * **NetworkX:** Built a weighted graph with nodes, edges, edge weights, and fixed coordinates to visualize the search space.
  * **Matplotlib:** Created step-by-step graph visualizations to highlight the currently expanded node and the final optimal path.
  * **Priority Queue (Heap):** Used Python's heapq to prioritize nodes based on the lowest evaluation function f(n) = g(n) + h(n).
  * **Heuristic Function:** Assigned heuristic values h(n) to estimate the remaining cost from each node to the goal.
  * **A Search:** Implemented a heuristic-based search algorithm that combines the actual path cost g(n) with the estimated cost h(n) to efficiently find the optimal path from the start node to the goal.

---

### 📍 Week 5: Beam Search Algorithm

* **Core Implementations:**
  * **NetworkX:** Constructed a directed graph with nodes, edges, heuristic values, and fixed coordinates to visualize the search structure.
  * **Matplotlib:** Created a graph visualization with color-coded nodes to distinguish the final path, selected nodes, unselected nodes, and discarded candidates.
  * **Heuristic Evaluation:** Assigned heuristic values h(n) to each node and sorted candidate nodes based on their estimated distance to the goal.
  * **Beam Width:** Implemented a configurable beam width to retain only the best W candidate nodes at each search level, reducing memory and search complexity.
  * **Beam Search:** Developed a heuristic-based search algorithm that explores the most promising nodes level-by-level while discarding less promising candidates to efficiently reach the goal.

---

### 📍 Week 6: AO* Search Algorithm

* **Core Implementations:**
  * **AND-OR Graph:** Represented a problem using an AND-OR graph where OR nodes select the most promising alternative and AND nodes require multiple child nodes to be solved together.
  * **Heuristic Function:** Assigned heuristic values h(n) to estimate the remaining cost from each node to the goal and guide the search toward promising solutions.
  * **Cost Calculation:** Calculated the cost of OR and AND branches to determine the minimum-cost solution. For an OR node, the minimum-cost child is selected, while an AND node combines the costs of all required children.
  * **Backtracking:** Updated the estimated costs of parent nodes after solving their child nodes and propagated the improved values backward through the graph.
  * **AO_star Search:** Implemented a heuristic-driven algorithm that recursively expands the most promising solution graph and continues updating costs until the optimal solution subgraph is identified.
  * **Graph Visualization:** Used NetworkX and Matplotlib to visualize AND/OR relationships, explored nodes, selected solution branches, and the final optimal solution graph.

---

### 📍 Week 7: [Coming Soon - Every Thursday]

* **Core Implementations:**
  * [Coming Soon]
  * [Coming Soon]

