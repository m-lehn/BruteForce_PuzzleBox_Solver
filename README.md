# 🧩 Roadside Puzzle Box — Notebook Playground

*A one-notebook exploration of packing wooden blocks into a perfect cube.*  
Three approaches inside the notebook — the first two fail (in funny ways), the third is a more systematic attempt you can extend.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1e3zVR8GNugbc1tMGRADX7HYg3xfbNKfv?usp=sharing)

---

## 📸 Puzzle & Pieces

![box](https://github.com/user-attachments/assets/952bf6ec-cc84-41e0-801b-ca6dc2c9c3a6)


The puzzle: stack a set of wooden blocks to form a bigger cube that fits the box.

**Block inventory (as axis-aligned rectangular prisms, size in unit cubes):**
```python
cubes = {
    (3, 2, 2): 6,
    (4, 2, 1): 6,
    (1, 1, 1): 5,
}
