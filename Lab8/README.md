# Lab 8 — K-Nearest Neighbors (KNN)

## 📌 Overview
This lab covers the K-Nearest Neighbors algorithm — a simple yet powerful instance-based learning method used for both classification and regression. KNN makes predictions based on the similarity between data points.

## 🎯 Objectives
- Understand the intuition behind KNN
- Implement KNN classification using Scikit-learn
- Tune the `k` hyperparameter to optimize performance
- Evaluate model performance and understand its strengths and limitations

## 📁 Files
| File | Description |
|------|-------------|
| `02-K Nearest Neighbors Assignment.Fahad.ipynb` | Main lab notebook implementing KNN |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`KNeighborsClassifier`, `train_test_split`, `StandardScaler`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `02-K Nearest Neighbors Assignment.Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### How KNN Works
1. Choose the number of neighbors `k`
2. Calculate the distance between the query point and all training points
3. Select the `k` closest neighbors
4. Predict by majority vote (classification) or average (regression)

### Distance Metrics
| Metric | Formula |
|--------|---------|
| **Euclidean** | `√Σ(xᵢ - yᵢ)²` — most common |
| **Manhattan** | `Σ|xᵢ - yᵢ|` — robust to outliers |
| **Minkowski** | Generalization of both |

### Choosing `k`
- Small `k` → low bias, high variance (overfitting)
- Large `k` → high bias, low variance (underfitting)
- Use cross-validation to find the optimal `k`

### Important Notes
- **Feature scaling is critical** — KNN is distance-based, so always standardize features first
- KNN is a **lazy learner** — no training phase, all computation happens at prediction time
- Computationally expensive on large datasets

---
*Course: Machine Learning — IAU | Author: Fahad*
