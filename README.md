# 🧩 Roadside Puzzle Box — Notebook Playground

*A one-notebook exploration of packing wooden blocks into a perfect cube.*  
Three approaches (the first two fail) inside the notebook you can extend.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1e3zVR8GNugbc1tMGRADX7HYg3xfbNKfv?usp=sharing)

---

## 📸 Puzzle & Pieces


<img width="965" height="366" alt="box" src="https://github.com/user-attachments/assets/a81d159c-bba6-41d3-8ac9-2c29ba6bc0eb" />


The puzzle: stack a set of wooden blocks to form a bigger cube that fits the box.

**Block inventory (as axis-aligned rectangular prisms, size in unit cubes):**
```python
cubes = {
    (1, 1, 1): 5, # id 0
    (3, 2, 2): 6, # id 1
    (4, 2, 1): 6, # id 2
}

solution = [
    [[2 1 1 2 2]
    [2 1 1 1 1]
    [2 1 1 1 1]
    [2 2 2 2 2]
    [0 2 2 2 2]]
    
    [[2 1 1 2 2]
    [2 1 1 1 1]
    [2 1 1 1 1]
    [2 0 1 1 1]
    [2 2 1 1 1]]
    
    [[1 1 1 2 2]
    [1 1 1 1 1]
    [1 1 0 1 1]
    [1 1 1 1 1]
    [2 2 1 1 1]]
    
    [[1 1 1 2 2]
    [1 1 1 0 2]
    [1 1 1 1 2]
    [1 1 1 1 2]
    [2 2 1 1 2]]
    
    [[2 2 2 2 0]
    [2 2 2 2 2]
    [1 1 1 1 2]
    [1 1 1 1 2]
    [2 2 1 1 2]]
]
