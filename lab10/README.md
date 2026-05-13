# Lab 10 — Random Forest Project (Extended)

## 📌 Overview
This lab is a deeper project-level application of Decision Trees and Random Forests introduced in Lab 9. It focuses on applying these algorithms to a more complex or extended dataset, with emphasis on hyperparameter tuning and model optimization.

## 🎯 Objectives
- Apply Random Forest to a full project-level problem
- Tune hyperparameters using GridSearchCV or RandomizedSearchCV
- Analyze feature importances to understand model behavior
- Compare model performance across different configurations

## 📁 Files
| File | Description |
|------|-------------|
| `02-Decision Trees and Random Forest Project.Fahad.ipynb` | Extended Random Forest project notebook |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`RandomForestClassifier`, `GridSearchCV`, `RandomizedSearchCV`, `feature_importances_`)
- Matplotlib / Seaborn

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `02-Decision Trees and Random Forest Project.Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Hyperparameter Tuning
| Parameter | Description |
|-----------|-------------|
| `n_estimators` | Number of trees in the forest |
| `max_depth` | Maximum depth of each tree |
| `min_samples_split` | Minimum samples required to split a node |
| `min_samples_leaf` | Minimum samples required at a leaf node |
| `max_features` | Number of features to consider at each split |

### GridSearchCV vs RandomizedSearchCV
- **GridSearchCV**: Exhaustive search over all combinations — thorough but slow
- **RandomizedSearchCV**: Random sampling of combinations — faster, good for large spaces

### Feature Importance Analysis
- Identifies which features contribute most to predictions
- Helps in dimensionality reduction and model interpretation

### Cross-Validation
- K-Fold CV ensures the model generalizes across different data splits
- Prevents overfitting to a single train/test split

---
*Course: Machine Learning — IAU | Author: Fahad*
