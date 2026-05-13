# Lab 4 — Data Quality Assessment & Preprocessing

## 📌 Overview
Raw data is rarely clean. This lab covers the essential techniques for assessing data quality and preprocessing it before feeding it into a machine learning model. Clean data leads to better, more reliable models.

## 🎯 Objectives
- Identify and handle missing values
- Detect and treat outliers
- Encode categorical variables
- Scale and normalize numerical features
- Split data into training and testing sets

## 📁 Files
| File | Description |
|------|-------------|
| `4- Data Quality Assessment & Preprocessing_Fahad.ipynb` | Main lab notebook covering all preprocessing steps |
| `README.md` | This file |

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`preprocessing`, `model_selection`)
- Matplotlib / Seaborn *(for visualizing distributions)*

## 🚀 How to Run
1. Launch Jupyter: `jupyter notebook`
2. Open `4- Data Quality Assessment & Preprocessing_Fahad.ipynb`
3. Run cells sequentially with `Shift + Enter`

## 📚 Key Concepts

### Missing Data
- Detection: `.isnull().sum()`
- Strategies: dropping rows/columns, mean/median/mode imputation

### Outlier Detection
- IQR method
- Z-score method
- Visualization via box plots

### Encoding
- Label Encoding
- One-Hot Encoding (`pd.get_dummies`)

### Feature Scaling
- Min-Max Normalization
- Standardization (Z-score scaling)

### Train/Test Split
- `train_test_split()` from Scikit-learn
- Importance of avoiding data leakage

---
*Course: Machine Learning — IAU | Author: Fahad*
