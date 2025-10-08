# Shortest Path Algorithm Comparison

A comparative analysis of three different approaches to solving the shortest path problem on a 2D grid with obstacles:
- **D-Wave Quantum CQM** (Constrained Quadratic Model)
- **PuLP** (Linear Programming with CBC/Gurobi solver)
- **NetworkX** (Dijkstra's Algorithm)

## 🎯 Features

- Support for diagonal movements with configurable weights
- Random obstacle generation
- Visual comparison of paths from different algorithms
- Side-by-side performance metrics
- Easy-to-use modular code structure

## 📊 Screenshots

### Path Comparison Visualization
![Path Comparison](screenshots/path_comparison.png)
*Comparison of paths found by different algorithms on a 10x10 grid*

### Algorithm Performance
![Performance Metrics](screenshots/performance_metrics.png)
*Total path weights for each algorithm*

## 🚀 Installation

### Prerequisites
```bash
pip install matplotlib networkx pulp
