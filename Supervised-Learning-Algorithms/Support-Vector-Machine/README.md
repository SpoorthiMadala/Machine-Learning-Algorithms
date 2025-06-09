# Support Vector Machines (SVM)

This project contains implementations and explanations of Support Vector Machine (SVM) algorithms for both classification and regression tasks. It covers the two main variants:

- **Support Vector Classification (SVC)**: A supervised learning method used for classification problems. It finds the optimal hyperplane that best separates different classes in the feature space.

- **Support Vector Regression (SVR)**: An extension of SVM for regression problems. SVR tries to fit a function within a specified margin of tolerance while maintaining model complexity.

---

## Contents

- `SVC.ipynb`: Implementation of SVM for classification problems. Includes:
  - Data preprocessing
  - Model training and hyperparameter tuning
  - Evaluation metrics such as accuracy, precision, recall, F1-score, and confusion matrix
  - Visualization of decision boundaries

- `SVR.ipynb`: Implementation of SVM for regression problems. Includes:
  - Data preprocessing
  - Model training and hyperparameter tuning
  - Evaluation metrics such as Mean Squared Error (MSE), R-squared (R²) score
  - Visualization of regression line and residuals

---

## Support Vector Classification (SVC)

SVC aims to find the maximum margin hyperplane that separates classes with the highest confidence. Key points:

- Works well for linear and non-linear classification using kernel functions (linear, polynomial, RBF, sigmoid)
- Effective in high-dimensional spaces
- Robust against overfitting, especially in cases where number of features is greater than number of samples

## Support Vector Regression (SVR)

SVR applies the same principles of SVM to regression. It tries to fit a curve within a margin (epsilon) and penalizes points outside the margin. Key points:

- Supports different kernels for non-linear regression
- Controls the trade-off between model complexity and the amount up to which deviations larger than epsilon are tolerated
- Useful in cases where relationships between variables are not strictly linear

---

## How to Use

1. Open and run the respective Jupyter notebooks (`SVC.ipynb` and `SVR.ipynb`).
2. Explore different kernels and hyperparameters.
3. Analyze performance metrics and visualizations.
4. Modify the code to apply SVM to your own datasets.

---

