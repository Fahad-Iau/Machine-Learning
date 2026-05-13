# Lab 6 — Regression Analysis & Feature Engineering

## 📌 Overview
Building on Lab 5, this lab explores more advanced regression techniques and the impact of feature engineering on model performance. It reinforces how thoughtful feature selection and transformation can significantly improve predictions.

## 🎯 Objectives
- Apply feature engineering techniques to improve regression models
- Explore polynomial regression for non-linear relationships
- Compare model performance with and without engineered features
- Understand regularization concepts (Ridge / Lasso)

## 📁 Files
| File | Description |
|------|-------------|
| `lab6-Fahad.ipynb` | Main lab notebook on advanced regression |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`LinearRegression`, `PolynomialFeatures`, `Ridge`, `Lasso`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `lab6-Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Feature Engineering
- Creating new features from existing ones
- Log transformations for skewed data
- Interaction terms between features

### Polynomial Regression
- Capturing non-linear patterns using `PolynomialFeatures`
- Risk of overfitting with high-degree polynomials

### Regularization
| Method | Description |
|--------|-------------|
| **Ridge (L2)** | Penalizes large coefficients, keeps all features |
| **Lasso (L1)** | Can zero out coefficients, performs feature selection |

### Bias-Variance Tradeoff
- Underfitting (high bias) vs. Overfitting (high variance)
- Using cross-validation to find the sweet spot

---
*Course: Machine Learning — IAU | Author: Fahad*
