# 🧭 Path Finder Visualizer

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Algorithm](https://img.shields.io/badge/Algorithm-BFS-green)

A **terminal-based Path Finding Visualizer** built using **Python** that demonstrates how the **Breadth First Search (BFS)** algorithm explores a maze to find the shortest path.

The project uses the **curses library** to animate the exploration process directly in the terminal.

---

# 🚀 Demo

The algorithm explores the maze step-by-step and visually highlights the path being explored until the destination is found.

```
Start: O
End:   X
Wall:  #
Path:  empty space
```

Example visualization in terminal:

```
# O # # # # # # #
#       #       #
#   # #   # #   #
#   #     #     #
#   # # # #     #
#       #       #
# # # # # # # X #
```

The algorithm searches until it finds the **shortest path from O to X**.

---

# 🧠 Algorithm Used

## Breadth First Search (BFS)

Breadth First Search is a graph traversal algorithm that explores nodes **level by level**.

### Steps

1️⃣ Start from the **source node (O)**
2️⃣ Add it to a **queue**
3️⃣ Visit all neighboring nodes
4️⃣ Mark nodes as **visited**
5️⃣ Continue exploring until **destination (X)** is found

### Why BFS?

✔ Guarantees **shortest path in an unweighted grid**
✔ Simple and efficient
✔ Commonly used in **maze solving and pathfinding**

---

# 📂 Project Structure

```
path-finder-visualizer
│
├── path_finder.py
├── README.md
├── requirements.txt
├── .gitignore
└── images
    └── demo.png
```

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/path-finder-visualizer.git
```

### 2️⃣ Navigate to project folder

```
cd path-finder-visualizer
```

### 3️⃣ Run the program

```
python path_finder.py
```

---

# 🛠️ Requirements

Python **3.x**

Libraries used:

```
curses
queue
time
```

These libraries are included in Python’s **standard library**.

---

# 📸 Screenshot

image.png

---

# 💡 Learning Outcomes

This project helps understand:

* Graph traversal algorithms
* Breadth First Search
* Queue data structure
* Pathfinding in grids
* Terminal UI using curses
