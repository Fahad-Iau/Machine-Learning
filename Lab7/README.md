# Lab 7 — Logistic Regression

## 📌 Overview
This lab transitions from regression to classification. Logistic Regression is a powerful and interpretable algorithm for binary and multi-class classification problems. This lab covers building, training, and evaluating a Logistic Regression classifier.

## 🎯 Objectives
- Understand the difference between regression and classification
- Learn how Logistic Regression uses the sigmoid function to output probabilities
- Build and train a Logistic Regression model with Scikit-learn
- Evaluate classifier performance using classification metrics

## 📁 Files
| File | Description |
|------|-------------|
| `02-Logistic Regression Assignment-Fahad Lab7.ipynb` | Main lab notebook implementing Logistic Regression |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`LogisticRegression`, `train_test_split`, `classification_report`, `confusion_matrix`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `02-Logistic Regression Assignment-Fahad Lab7.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Sigmoid Function
- Maps any real number to a probability between 0 and 1
- `σ(z) = 1 / (1 + e^(-z))`

### Decision Boundary
- Threshold (default 0.5) determines class assignment
- Can be adjusted based on problem requirements

### Model Evaluation
| Metric | Description |
|--------|-------------|
| **Accuracy** | Overall correct predictions |
| **Precision** | True positives out of all predicted positives |
| **Recall** | True positives out of all actual positives |
| **F1-Score** | Harmonic mean of precision and recall |
| **Confusion Matrix** | Full breakdown of TP, TN, FP, FN |
| **ROC-AUC** | Area under the ROC curve |

### Multiclass Extension
- One-vs-Rest (OvR)
- Softmax (Multinomial Logistic Regression)

---
*Course: Machine Learning — IAU | Author: Fahad*
