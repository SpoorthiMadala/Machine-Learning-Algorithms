# K-Nearest Neighbors (KNN)

This project demonstrates both **classification** and **regression** using the **K-Nearest Neighbors (KNN)** algorithm, implemented with Scikit-learn. KNN is a **non-parametric**, **instance-based** learning algorithm that makes predictions based on the similarity of input data points.

---

## Contents

- Introduction to KNN
- KNN for Classification
- KNN for Regression
- Evaluation and Visualization
- Key Insights and Limitations

---

## 1. Overview of KNN

KNN is a lazy learning algorithm that stores the training dataset and makes predictions by computing the distance between new data points and existing ones. It uses the majority class (classification) or the average target value (regression) of the *k* nearest neighbors to make predictions.

---

## 2. KNN Classification

### Dataset
We use the **Breast Cancer Wisconsin dataset**, which contains features extracted from digitized images of a breast mass.

### Steps Involved:
- Load and standardize the data
- Split into training and test sets
- Train `KNeighborsClassifier`
- Evaluate accuracy, classification report, and confusion matrix
- Visualize performance using Seaborn

---

## 3. KNN Regression

### Dataset
We use the **California Housing dataset**, which contains features of California districts to predict median house value.

### Steps Involved:
- Load and standardize the data
- Select a target feature
- Train `KNeighborsRegressor`
- Evaluate model with Mean Squared Error and R² Score
- Visualize predictions vs actual values

---

## 4. Evaluation

For classification:
- **Accuracy Score**
- **Classification Report**
- **Confusion Matrix** (visualized)

For regression:
- **Mean Squared Error (MSE)**
- **R-squared (R²) Score**
- **Regression plot** (Actual vs Predicted)

---

## 5. Key Insights

- KNN performs well with small datasets and when decision boundaries are nonlinear.
- Model performance heavily depends on the choice of **k** and the **distance metric**.
- KNN is sensitive to feature scaling and the curse of dimensionality.

---

## 6. Limitations

- High computational cost during prediction (no training phase).
- Inefficient with large datasets.
- Requires feature normalization for optimal results.

---

