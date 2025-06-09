# Logistic Regression

This project demonstrates the application of **Logistic Regression**. The implementation is done using Python and scikit-learn.

---

## Objective

To build a binary classifier that predicts whether a tumor is **malignant** or **benign** using patient diagnostic data. Logistic Regression is selected for its simplicity, interpretability, and effectiveness in binary classification tasks.

---

## Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Features**: 30 numeric features (e.g., radius, texture, smoothness)
- **Target**: 
  - `0` → Malignant  
  - `1` → Benign

---

## Workflow

1. **Data Loading**
   - Use `load_breast_cancer()` from scikit-learn
2. **Data Preprocessing**
   - Apply standardization using `StandardScaler`
   - Split into training and test sets
   
3. **Model Building**
   - Train logistic regression using `LogisticRegression(max_iter=10000)`
4. **Evaluation**
   - Accuracy
   - Classification report (Precision, Recall, F1-score)
   - ROC-AUC Score
   - Confusion matrix
5. **Visualization**
   - Confusion matrix heatmap (using Seaborn)
   - ROC curve plot

---



## Key Learnings

- Logistic Regression is efficient for linearly separable binary classification problems.
- Feature scaling significantly improves performance and convergence.




