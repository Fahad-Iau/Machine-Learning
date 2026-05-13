# Lab 11 — Credit Card Customer Segmentation

## 📌 Overview
This lab introduces **unsupervised learning** through a real-world customer segmentation problem. Using credit card customer data, clustering algorithms are applied to group customers into meaningful segments — a technique widely used in marketing, finance, and product strategy.

## 🎯 Objectives
- Understand the difference between supervised and unsupervised learning
- Apply K-Means clustering to segment customers
- Determine the optimal number of clusters using the Elbow Method and Silhouette Score
- Visualize and interpret customer segments

## 📁 Files
| File | Description |
|------|-------------|
| `02-Credit Card Customer Segmentation Assignment Fahad.ipynb` | Main lab notebook for customer segmentation |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`KMeans`, `StandardScaler`, `PCA`, `silhouette_score`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `02-Credit Card Customer Segmentation Assignment Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Unsupervised Learning
- No labels — the algorithm discovers hidden structure in data
- Goal: find natural groupings (clusters) within the data

### K-Means Clustering
1. Choose `k` (number of clusters)
2. Initialize `k` centroids randomly
3. Assign each point to the nearest centroid
4. Recalculate centroids as the mean of assigned points
5. Repeat until convergence

### Choosing the Right `k`
| Method | Description |
|--------|-------------|
| **Elbow Method** | Plot inertia vs. k; look for the "elbow" point |
| **Silhouette Score** | Measures how similar a point is to its own cluster vs. others |

### Dimensionality Reduction for Visualization
- **PCA (Principal Component Analysis)**: Reduces high-dimensional data to 2D/3D for plotting clusters visually

### Business Interpretation
- Segment customers by spending behavior, credit limit, payment patterns
- Enables targeted marketing, risk assessment, and personalized offers

---
*Course: Machine Learning — IAU | Author: Fahad*
