# Diagnostic Feature Analysis

## Project Goal
Exploratory data analysis (EDA) and machine learning on the Wisconsin Breast Cancer dataset. This is the first portfolio project — built during Summer 2026 before junior year at UNCC. It lives at `HeidiW-PPP/Diagnostic-Feature-Analysis` on GitHub.

## About Heidi
Non-traditional student (age 40, 23yr work experience), UNCC junior — CS BA, Bioinformatics concentration, Software Dev + Data Science minors. Graduation ~Spring 2028. Goal: employment in bioinformatics/software dev/data science as quickly as possible after grad.

**This is a learning project.** Heidi is building Python/data science skills, not just shipping code. Explain the *why* behind each step. When introducing a new concept (a pandas method, a sklearn class, a statistical idea), give a one-sentence explanation of what it does and why we're using it here. Don't assume prior familiarity with the data science stack.

## Notebook Structure (planned)
1. **Dataset** — load the Wisconsin Breast Cancer dataset, understand its source and structure
2. **EDA** — shape, dtypes, missing values, class balance, feature distributions, correlations
3. **Preprocessing** — train/test split, feature scaling
4. **Modeling** — at least two classifiers (e.g. logistic regression + random forest), compare performance
5. **Evaluation** — confusion matrix, precision/recall/F1, ROC curve
6. **Summary** — key findings, what the features tell us, what the model learned

## Technical Stack
- Python 3, Jupyter notebook (`analysis.ipynb`)
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` for modeling and evaluation
- Dataset: Wisconsin Breast Cancer — available via `sklearn.datasets.load_breast_cancer()`

## Style Notes
- Keep code cells focused — one concept per cell
- Markdown cells before each section to explain what we're about to do and why
- Prefer readable variable names over clever one-liners
- Don't rush to the model — the EDA section should be thorough