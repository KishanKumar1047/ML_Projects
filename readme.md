# 🧠 ML Regression Projects Portfolio

Welcome to my Machine Learning Regression Projects repository! This collection includes foundational regression models built using Python and libraries like **scikit-learn**, **NumPy**, and **Pandas**. These projects helped me understand and implement key techniques in supervised learning for predicting continuous values.

---

## 📁 Project Structure


Each folder contains:
- Clean, well-commented Jupyter notebooks or `.py` files
- Input dataset (or link to dataset)
- Model training, evaluation, and visualization

---

## 🚀 Projects Overview

### 🔹 Linear Regression
- Predicts a target variable using a single independent feature.
- Techniques: Cost function (MSE), Gradient Descent
- Example: Predicting student scores based on study hours
- Metrics: R² Score, MAE, MSE

### 🔹 Multiple Linear Regression
- Uses multiple features to predict a continuous target.
- Example: House price prediction using size, location, age, etc.
- Concepts: Feature scaling, multicollinearity

### 🔹 Ridge Regression (L2 Regularization)
- Penalizes large coefficients to reduce model complexity and prevent overfitting.
- Best for: Datasets with multicollinearity
- Hyperparameter: `alpha` (regularization strength)

### 🔹 Lasso Regression (L1 Regularization)
- Shrinks some coefficients to zero, effectively selecting important features.
- Ideal when: Feature selection is needed
- Visual Insight: Path of coefficients with changing `alpha`

### 🔹 Elastic Net Regression
- Combines L1 and L2 regularization (Lasso + Ridge).
- Balances between feature selection and coefficient shrinkage.
- Tunable Parameters: `alpha` and `l1_ratio`

---

## 📊 Evaluation Metrics
Used consistently across models:
- R² Score (Coefficient of Determination)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Cross-validation scores (where applicable)

---

## 🛠️ Libraries Used
- `numpy`
- `pandas`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ml-regression-projects.git
   cd ml-regression-projects
