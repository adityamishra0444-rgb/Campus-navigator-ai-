# Campus Navigator AI  
### A Simple Artificial Intelligence Search Project using BFS, DFS, and A*  
**By: Aditya Mishra **

---

## 📌 Project Overview
Campus Navigator AI is a simple Artificial Intelligence project that finds the best path between two campus locations.  
It uses **pure AI concepts from the syllabus**, NOT machine learning.

This project demonstrates:

- Problem-Solving Agents  
- State Space Representation  
- Uninformed Search → **BFS**, **DFS**  
- Informed Search → **A\***  
- Heuristic Function  
- Modular Agent Design

---

## 📂 Folder Structure

```
CampusNavigatorAI/
│
├── core/               # All AI logic & algorithms
│   ├── graph.py        # Campus graph (nodes & connections)
│   ├── search.py       # BFS, DFS, A*
│   ├── heuristic.py    # Heuristic values for A*
│   ├── agent.py        # Navigation Agent class
│   └── __init__.py
│
├── data/
│   └── nodes.csv       # Campus node data
│
├── docs/               # Diagrams & documentation
│   ├── class_diagram.png
│   ├── use_case.png
│   ├── sequence.png
│   └── architecture.png
│
├── tests/
│   ├── test_search.py  # Unit test for BFS
│   └── __init__.py
│
├── app.py              # MAIN file (run this)
├── README.md           # Project description
├── PROJECT_REPORT.md   # Full project report
└── requirements.txt    # Python dependencies
```

---

## ▶️ How To Run This Project

### 1️⃣ Open Terminal in VS Code
```
cd CampusNavigatorAI
```

### 2️⃣ Create virtual environment (optional)
```
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies
```
pip install -r requirements.txt
```

### 4️⃣ Run the AI Program
```
python app.py
```

Enter, for example:
```
Hostel
Library
```

---

## 🧠 Search Algorithms Used

### 🔷 BFS (Breadth-First Search)
- Uninformed search  
- Guarantees shortest path  
- Uses queue  

### 🔶 DFS (Depth-First Search)
- Explores deeper paths  
- Uses stack  

### ⭐ A* Search (Informed Search)
- Uses **f(n) = g(n) + h(n)**  
- Efficient for shortest paths  
- Uses heuristic values from `heuristic.py`

---

## 🧪 Running Unit Tests
Run the BFS test case:

```
pytest -q
```

---

## 📘 Concepts Covered (Viva + Syllabus)
- AI Agents  
- State Space Representation  
- BFS, DFS  
- A*  
- Heuristic Function  
- Graph representation  
- Python modular programming  
- Basic unit testing

---

## 💡 Example Output

```
=== Campus Navigation AI System ===
Enter start location: Hostel
Enter goal location: Library

--- RESULTS ---
BFS Path: ['Hostel', 'Canteen', 'Library']
DFS Path: ['Hostel', 'Block A', 'Block B', 'Block C', 'Library']
A* Path: ['Hostel', 'Canteen', 'Library']
```

---

## 👨‍💻 Author
**Aditya Mishra **  
B.Tech CSE 
VIT Bhopal University  
