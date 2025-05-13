# 🌐 Project 5 – Social Network (Spring 2025)

This project simulates a **social network** using Java and custom data structures. It focuses on building and analyzing a directed graph to explore key concepts in graph theory, social connections, and algorithmic applications.

I implemented core graph functionality, contact suggestion, influencer detection, and Kevin Bacon distance analysis. The project includes integration with a provided GUI for real-time visualization and interaction.

---

## 🧩 Key Components

### 1. `Graph310.java`
- Implements a custom **directed graph** using a map-of-maps (adjacency list).
- Manages vertex and edge operations, neighbors, in/out degrees, and incident data.
- Foundation for all algorithms and GUI operations.

### 2. `SuggestedContacts.java`
- Implements a **link prediction** algorithm based on common neighbors.
- Recommends potential connections ranked by similarity score.

### 3. `KevinBaconCalculator.java`
- Calculates the minimum number of directed jumps to reach the **Kevin Bacon** node.
- Uses BFS-like traversal to trace the shortest influence path.

### 4. `InfluencerDetection.java`
- Identifies **top influencers** in the network using the formula:

---

## 📌 Features

- Add and remove vertices and edges
- Analyze directed connections (followers vs. following)
- Detect top influencers based on in/out-degree ratio
- Suggest new contacts using shared neighbor logic
- Calculate shortest path to Kevin Bacon using directed graph traversal
- Visualize the network in a real-time GUI using the JUNG framework

---

## 📁 Project Files

- `Graph310.java`
- `SuggestedContacts.java`
- `KevinBaconCalculator.java`
- `InfluencerDetection.java`
- `SimGUI.java` (provided)
- `graph_data/` (provided example data files)

---

## ✅ Skills Demonstrated

- Graph theory (directed graphs, adjacency lists)
- Custom data structure design (map-of-maps)
- Traversal and search algorithms (BFS-style pathfinding)
- Sorting and filtering using `Comparator`
- GUI integration using JUNG layout and event triggers
- File I/O and simulation interaction

---

## 🧪 Testing Strategy

- Manual testing with the GUI
- Main methods in each class for feature-level testing
- Print-based validation 
- Simulate deletion, addition, and analysis of graph nodes and edges

---