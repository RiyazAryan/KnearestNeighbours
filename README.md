# KNN Customer Churn Classification

This repository contains a Jupyter notebook that demonstrates how to build a **K-Nearest Neighbors (KNN)** classifier to predict customer churn using the Telco Customer Churn dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`).

## 📦 What’s included

- **`.knn.ipynb`** – Notebook with data loading, preprocessing, model training, evaluation, and prediction steps.
- **`WA_Fn-UseC_-Telco-Customer-Churn.csv`** – Dataset used for training and evaluation.

## ✅ Requirements

A Python environment with the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Install Dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn
```

> Tip: If you use conda, you can run:
>
> ```bash
> conda install pandas numpy matplotlib seaborn scikit-learn
> ```

## ▶️ Running the notebook

1. Open the workspace in VS Code.
2. Open `.knn.ipynb`.
3. Run the cells in order (top → bottom).

## 🔍 What to explore next

- Tune `n_neighbors` and compare performance.
- Try other classifiers (Logistic Regression, Random Forest, etc.).
- Add cross-validation and/or grid search.
- Explore feature selection or dimensionality reduction.
