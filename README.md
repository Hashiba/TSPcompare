# Traveling Salesman Problem Comparison (TSPCompare001)

This Jupyter notebook demonstrates a simple brute-force approach to solving the **Traveling Salesman Problem (TSP)** using Python and NumPy. The notebook includes random city generation, distance matrix calculation, total route evaluation, and performance comparison for small-scale TSP instances.

---

## Files

- `TSPCompare001.ipynb` – Main Jupyter notebook with code and comments.
- No other dependencies or data files required.

---

## Features

- Generates random cities with coordinates.
- Computes Euclidean distance matrix.
- Evaluates all permutations of city paths (brute-force).
- Plots routes using Matplotlib.
- Measures computation time.

---

## Algorithms Used

- **Brute-force search**:
  - Tries every possible permutation of cities.
  - Guarantees the shortest route.
  - Scales poorly (factorial complexity), useful only for small `n`.

---

## Requirements

Install dependencies directly in your Jupyter notebook or via terminal:

### Notebook Cell (recommended):
```python
!pip install numpy matplotlib
