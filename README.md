# 🔢 NumPy Assignment — 1

A beginner-friendly NumPy practice assignment covering the most essential array creation functions. Solved in **Google Colab** using Python.

---

## 📚 Topics Covered

| Function | Description |
|---|---|
| `np.array()` | Create arrays from lists |
| `np.zeros()` | Arrays filled with zeros |
| `np.ones()` | Arrays filled with ones |
| `np.full()` | Arrays filled with a custom value |
| `np.arange()` | Evenly spaced values with a step |
| `np.linspace()` | Evenly spaced values between two points |
| `np.eye()` | Identity matrix |
| `np.random.randint()` | Random integer arrays |

---

## 🧩 Questions & Solutions

### Q1 — Create a NumPy Array
Create a NumPy array from `[10, 20, 30, 40, 50]`
```python
import numpy as np
array = np.array([10, 20, 30, 40, 50])
```
```
[10 20 30 40 50]
```

---

### Q2 — Create a 3×3 Matrix
Convert a nested list into a 2D NumPy array
```python
matrix = np.array([[1,2,3],[4,5,6],[7,8,9]])
```
```
[[1 2 3]
 [4 5 6]
 [7 8 9]]
```

---

### Q3 — Array of Zeros
Create an array of 5 zeros
```python
np.zeros(5)
```
```
[0. 0. 0. 0. 0.]
```

---

### Q4 — 2×4 Zero Matrix
```python
np.zeros([2, 4])
```
```
[[0. 0. 0. 0.]
 [0. 0. 0. 0.]]
```

---

### Q5 — Array of Ones
```python
np.ones(6)
```
```
[1. 1. 1. 1. 1. 1.]
```

---

### Q6 — Matrix Using `full()`
Create a 3×3 matrix filled with 9
```python
np.full([3, 3], 9)
```
```
[[9 9 9]
 [9 9 9]
 [9 9 9]]
```

---

### Q7 — Even Numbers Using `arange()`
Even numbers from 0 to 20
```python
np.arange(0, 20, 2)
```
```
[ 0  2  4  6  8 10 12 14 16 18]
```

---

### Q8 — Equally Spaced Values Using `linspace()`
6 values between 0 and 1
```python
np.linspace(0, 1, 6)
```
```
[0.  0.2 0.4 0.6 0.8 1. ]
```

---

### Q9 — Identity Matrix
5×5 identity matrix
```python
np.eye(5)
```
```
[[1. 0. 0. 0. 0.]
 [0. 1. 0. 0. 0.]
 [0. 0. 1. 0. 0.]
 [0. 0. 0. 1. 0.]
 [0. 0. 0. 0. 1.]]
```

---

### Q10 — Random Integer Matrix
3×3 matrix with random integers between 1 and 20
```python
np.random.randint(1, 20, (3, 3))
```
```
[[12  5 18]
 [ 3 15  9]
 [11  7 20]]
```

---

## 🚀 How to Run

### Option 1 — Google Colab *(Recommended)*
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` file
3. Run all cells — NumPy comes pre-installed ✅

### Option 2 — Local Setup
```bash
# Install NumPy
pip install numpy

# Run the notebook
jupyter notebook numpy_assignment.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3**
- **NumPy**
- **Google Colab / Jupyter Notebook**

---

## 👨‍🎓 About

This assignment was completed as part of my Python & Data Science learning journey.  
I'm documenting my progress publicly — follow along! 🌱

---

## 📄 License

This project is open source under the [MIT License](LICENSE).
