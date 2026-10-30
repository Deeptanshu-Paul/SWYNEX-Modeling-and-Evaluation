# SWYNEX - Modeling and Evaluation (Task 3)

Baseline modeling of a symptom-based disease classification dataset.

## Dataset
- Source: cleaned data from Task 1 (SWYNEX-Data-Preparation)
- 132 binary symptom features, target `prognosis` (41 diseases)

## Approach
1. Removed duplicate rows before splitting to prevent data leakage
2. Baseline: Logistic Regression
3. Compared with Bernoulli Naive Bayes and Random Forest
4. Evaluated with accuracy, macro precision, recall, F1, confusion matrix and cross-validation

## Key Result
[one sentence with your best scores]

## Limitations
See the notebook for the full discussion (duplicates, tiny test set, synthetic data).

## Files
- `Modeling_and_Evaluation.ipynb`: full notebook
- `Training_clean.csv`, `Testing_clean.csv`: datasets

## Tools
Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Google Colab
