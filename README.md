# Delhi Metro Network Analysis using Python 🏙️🚇

This project analyzes the Delhi Metro network using Python. It covers graph-based network analysis, station-level insights, and visualization techniques to understand the structure and efficiency of the metro system.

## 📌 Project Overview

The Delhi Metro is one of the largest and most complex rapid transit systems in the world. This notebook performs:

- **Graph construction** from metro lines.
- **Shortest path analysis** between stations.
- **Centrality and connectivity measures** using NetworkX.
- **Interactive visualization** of the metro network with `folium` and `plotly`.

## 🛠️ Tools and Libraries Used

- `pandas` – Data manipulation
- `networkx` – Graph and network analysis
- `folium` – Map visualization
- `plotly` – Interactive plotting
- `matplotlib` – Basic visualization

## 🧾 Features and Functionality

### ✅ Data Preprocessing
- Reads and cleans metro station and line data.
- Identifies unique metro lines and stations.

### ✅ Graph Construction
- Creates an undirected graph with stations as nodes and connections as edges.
- Assigns weight to edges based on the distance or travel time.

### ✅ Network Analysis
- Computes shortest paths between stations.
- Identifies most central or connected stations.
- Analyzes degree, betweenness, and closeness centrality.

### ✅ Visualizations
- Station-to-station connections on an interactive map.
- Visual plots showing node degrees, network structure, etc.
