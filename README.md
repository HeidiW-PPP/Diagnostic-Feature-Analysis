# Diagnostic Feature Analysis

Exploratory data analysis and binary classification on the Wisconsin Breast Cancer dataset.
Built as a portfolio project to demonstrate an end-to-end machine learning pipeline in Python.

## What this project covers

| Section | Description |
|---|---|
| Dataset | Load and inspect the Wisconsin Breast Cancer dataset via scikit-learn |
| EDA | Shape, dtypes, class balance, feature distributions, correlation analysis |
| Preprocessing | Train/test split, feature scaling with StandardScaler |
| Modeling | Logistic Regression and Random Forest classifiers |
| Evaluation | Confusion matrix, precision/recall/F1, ROC curves with AUC |
| Summary | Key findings and observations from the analysis |

## Dataset

The [Wisconsin Breast Cancer dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)
contains 569 samples with 30 numeric features computed from digitized fine needle aspirate (FNA)
images of breast masses. The target is binary: **malignant** or **benign**.

## Tech stack

- Python 3 · Jupyter Notebook
- `pandas` · `numpy` · `matplotlib` · `seaborn`
- `scikit-learn`

## How to run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
jupyter notebook analysis.ipynb
```

Then run all cells from top to bottom.

---

*First portfolio project — built Summer 2026.*
