# Lab 9 — Decision Trees & Random Forest

## 📌 Overview
This lab introduces tree-based learning methods — one of the most powerful and interpretable families of machine learning algorithms. Decision Trees form the foundation, and Random Forests extend them into an ensemble approach that dramatically improves accuracy and robustness.

## 🎯 Objectives
- Understand how Decision Trees split data using information gain and Gini impurity
- Build and visualize a Decision Tree classifier
- Implement a Random Forest and understand ensemble learning
- Compare the performance of a single tree vs. an ensemble

## 📁 Files
| File | Description |
|------|-------------|
| `02-Decision Trees and Random Forest Project.Fahad.ipynb` | Main lab notebook covering Decision Trees and Random Forest |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`DecisionTreeClassifier`, `RandomForestClassifier`, `train_test_split`)
- Matplotlib / Seaborn
- `plot_tree` for visualization

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `02-Decision Trees and Random Forest Project.Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Decision Trees
- **Splitting criteria**: Gini Impurity, Entropy (Information Gain)
- **Tree depth**: Controls overfitting — deeper trees memorize training data
- **Pruning**: Reducing tree size to improve generalization

### Random Forest
- An **ensemble** of many decision trees
- Each tree is trained on a random subset of data (**Bagging**) and features
- Final prediction = majority vote of all trees

### Why Random Forest > Single Tree?
| Property | Decision Tree | Random Forest |
|----------|--------------|---------------|
| Variance | High | Low |
| Overfitting | Prone | Resistant |
| Interpretability | High | Lower |
| Accuracy | Moderate | High |

### Feature Importance
- Random Forest provides a ranking of which features matter most
- Useful for feature selection in subsequent steps

---
*Course: Machine Learning — IAU | Author: Fahad*
