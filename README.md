# Polynomial-Regression-of-salary-dataset

# Polynomial Regression on Salary Dataset

This notebook demonstrates how to apply Polynomial Regression to model non-linear relationships in a salary dataset.

---

## 📌 What It Does

- Loads a salary dataset (Position vs. Salary)
- Applies `PolynomialFeatures` to capture non-linearity
- Trains a `LinearRegression` model on the transformed data
- Visualizes the results with both linear and polynomial curves
- Predicts salary for new input levels

---

## 📊 Dataset Overview

The dataset typically includes:
- `Level`: Position level or rank
- `Salary`: Corresponding salary for that position

---

## 🧠 Key Concepts

- Polynomial Regression allows linear models to fit non-linear data by transforming input features into polynomial combinations.
- Equation used:
  
  \[
  y = \theta_0 + \theta_1·x + \theta_2·x^2 + \dots + \theta_n·x^n
  \]

- The degree of the polynomial (e.g., 2, 3, 4, 6) affects the curve shape and model complexity.

---

## 🧰 Libraries Used

- `numpy`
- `matplotlib`
- `pandas`
- `sklearn.preprocessing.PolynomialFeatures`
- `sklearn.linear_model.LinearRegression`

---

## ▶️ How to Run

1. Open the notebook:
   ```bash
   jupyter notebook "Copy of Polynomial Regression Working Copy (Salary Data - After SVR).ipynb"
