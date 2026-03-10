# Mastering N-Dimensional Arrays with NumPy

This repository contains a comprehensive breakdown of array structures in NumPy, ranging from simple 1-D vectors to complex 4-D tensors. Understanding these structures is fundamental for Data Science, Image Processing, and Deep Learning.

## 🧮 Mathematical Breakdown

In NumPy, the **Size** of an array (the total number of elements) is calculated using the product of its **Shape**.

### The Size Formula
For any array with shape $(d_1, d_2, ..., d_n)$, the total size is:
$$\text{Size} = d_1 \times d_2 \times ... \times d_n$$

### Example: Your 4-D Array
In the provided code, `arr4` has a shape of **(3, 3, 3, 3)**.
- **Calculation:** $3 \times 3 \times 3 \times 3 = 81$
- **Interpretation:** You have **3** blocks, each containing **3** matrices, where each matrix has **3** rows and **3** columns.

---

## 🚀 Applications of N-Dimensional Arrays


| Dimension | Shape Representation | Real-World Application |
| :--- | :--- | :--- |
| **1-D** | `(x,)` | Simple lists, Time-series data, Sensor signals. |
| **2-D** | `(rows, cols)` | Spreadsheets (Excel), Grayscale images, Weight matrices. |
| **3-D** | `(depth, rows, cols)` | RGB Images (3 color channels), Video (frames, h, w). |
| **4-D** | `(batch, depth, rows, cols)` | Machine Learning batches, Medical Imaging (MRI scans over time). |

---

## 💻 How to Run
1. Ensure you have NumPy installed:
   ```bash
   pip install numpy
