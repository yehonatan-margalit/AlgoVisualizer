# 🧠 Interactive Algorithm Visualizer Lab

Welcome to the Algorithm Lab! 
This project is an interactive visualization tool designed to take the dry theory of Graph Algorithms and turn it into something you can see, touch, and truly understand. Built as a study aid for Computer Science students at Bar-Ilan University, it's perfect for anyone looking to deeply grasp core CS algorithms.

🚀 **[Click here for the Live Demo](https://yehonatan-margalit.github.io/AlgoVisualizer/)**

## 🎯 What's Inside?
The system is divided into 3 main workspaces, covering the core topics of graph theory:

### 1. 🛤️ Shortest Paths & Traversals (Directed Graphs)
* **Depth-First Search (DFS):** Watch discovery/finish times ($d, f$) and the Call Stack in real-time.
* **Breadth-First Search (BFS):** Visualize the Queue, node distances, and visual level-based coloring.
* **Dijkstra's Algorithm:** Find the shortest path using a Priority Queue and edge relaxation.
* **Bellman-Ford:** Handle negative weights and automatically detect negative cycles.

### 2. 🌲 Minimum Spanning Tree - MST (Undirected Graphs)
* **Prim's Algorithm:** Grow the MST node-by-node using a priority-based selection.
* **Kruskal's Algorithm:** Global edge sorting, adding edges to the tree while rejecting those that form cycles (simulating Union-Find).

### 3. 🌊 Flow Networks (Max Flow)
* **Edmonds-Karp:** Find augmenting paths in the residual graph using BFS and push flow step-by-step (displaying the bottleneck).
* **Dinic's Algorithm:** A spectacular visual breakdown into phases: Building a **Level Graph** (with dynamic color-coding for distances), followed by finding a **Blocking Flow** using DFS. Includes an auto-run feature for full visualization.

## ✨ Special Features
* **💡 Exam Insights Panel:** A built-in theoretical cheat sheet covering time complexities ($O$), space complexities, and classic use cases for each algorithm.
* **📦 Real-time Data Structures Window:** Peek "into the memory" of the algorithm and watch the Queue, Stack, or Priority Queue change in real-time.
* **✏️ Dynamic Graph Editor:** Users can click the canvas to add nodes, drag between nodes to create edges, and set custom weights or capacities.

## 🛠️ Technologies Used
The project is built as a Single Page Application (SPA) running entirely on the Client-side, allowing instant loading with zero backend setup:
* **HTML5 & CSS3** for a clean, modern UI/UX.
* **JavaScript (Vanilla JS)** for the pure algorithmic logic and execution engine.
* **[Cytoscape.js](https://js.cytoscape.org/)** - A powerful graph theory rendering engine for network visualization.

## 👨‍💻 About
Developed by **Yehonatan Margalit**.
This tool was built as a hands-on educational project to demonstrate and sharpen theoretical algorithmic understanding.

---
*Did you find this tool helpful for your algorithm exams? Consider giving the project a ⭐️ Star!*