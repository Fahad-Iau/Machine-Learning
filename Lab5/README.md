# Lab 5 — Linear Regression

## 📌 Overview
This lab introduces Linear Regression — one of the foundational supervised learning algorithms. The goal is to understand how to model relationships between features and a continuous target variable, and evaluate model performance.

## 🎯 Objectives
- Understand the theory behind Simple and Multiple Linear Regression
- Build a regression model using Scikit-learn
- Evaluate model performance using standard regression metrics
- Visualize the regression line and residuals

## 📁 Files
| File | Description |
|------|-------------|
| `lab5-Fahad.ipynb` | Main lab notebook implementing Linear Regression |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`LinearRegression`, `train_test_split`, `metrics`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `lab5-Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Simple Linear Regression
- Models the relationship between one feature and a target: `y = mx + b`

### Multiple Linear Regression
- Extends to multiple input features: `y = w₁x₁ + w₂x₂ + ... + b`

### Model Evaluation Metrics
| Metric | Description |
|--------|-------------|
| **MAE** | Mean Absolute Error — average absolute difference |
| **MSE** | Mean Squared Error — penalizes large errors more |
| **RMSE** | Root MSE — same unit as target variable |
| **R²** | Coefficient of determination — how well model explains variance |

### Assumptions of Linear Regression
- Linearity
- Independence of errors
- Homoscedasticity
- Normality of residuals

---
*Course: Machine Learning — IAU | Author: Fahad*
