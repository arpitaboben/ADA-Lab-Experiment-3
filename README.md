# Graph Algorithms Mini Project

## ADA Lab Experiment 3
Arpita

---

# Project Overview

This project implements fundamental **Graph Algorithms** to demonstrate how graphs are used to solve real-world problems such as network routing, social media connections, and infrastructure planning.

Graphs are widely used in areas like transportation systems, computer networks, project scheduling, and social networks. This project explores how algorithms efficiently process and analyze graph structures.

---

# Objectives

* Represent graphs using **Adjacency List and Adjacency Matrix**
* Implement **Graph Traversal Algorithms**
* Implement **Topological Sorting**
* Implement **Shortest Path Algorithms**
* Implement **Minimum Spanning Tree Algorithms**
* Analyze time complexity and real-world applications

---

# Implemented Algorithms

## 1. Graph Representation

Graphs are represented using:

* Adjacency List
* Adjacency Matrix

These representations help efficiently store graph data depending on graph density.

---

## 2. Breadth First Search (BFS)

**Description:**
BFS explores nodes level by level using a queue.

**Application:**
Friend recommendation systems in social networks.

**Time Complexity:**
O(V + E)

---

## 3. Depth First Search (DFS)

**Description:**
DFS explores nodes deeply before backtracking.

**Applications:**

* Web crawling
* Cycle detection
* Maze solving

**Time Complexity:**
O(V + E)

---

## 4. Topological Sorting

**Description:**
Topological sorting orders nodes in a Directed Acyclic Graph (DAG).

**Application:**
Task scheduling in project management.

**Time Complexity:**
O(V + E)

---

## 5. Dijkstra Algorithm

**Description:**
Finds the shortest path between nodes in a weighted graph.

**Application:**
Navigation systems such as Google Maps.

**Time Complexity:**
O((V + E) log V)

---

## 6. Minimum Spanning Tree (Prim's Algorithm)

**Description:**
Constructs a tree connecting all vertices with minimum total edge weight.

**Applications:**

* Network cabling
* Electrical grid planning
* Road network optimization

**Time Complexity:**
O(E log V)

---

# Technologies Used

* Python 3
* Jupyter Notebook
* Matplotlib (optional for visualization)

---

# Project Structure

ADA-Lab-Experiment-3

README.md
requirements.txt
graph_realworld.ipynb


---

# Setup Instructions

1. Clone the repository

git clone https://github.com/arpitaboben/ADA-Lab-Experiment-3

2. Navigate into the project folder

cd graph-algo-mini-project-arpita

3. Create a virtual environment

python -m venv .venv

4. Activate environment

Windows
.venv\Scripts\activate

Mac/Linux
source .venv/bin/activate

5. Install dependencies

pip install -r requirements.txt

6. Run Jupyter Notebook

jupyter notebook

Open **graph_realworld.ipynb** and run all cells.

---

# Conclusion

This project demonstrates how graph algorithms can be used to solve real-world problems involving connectivity, routing, and optimization. Understanding these algorithms provides a strong foundation for building scalable systems in networking, transportation, and data analysis.
