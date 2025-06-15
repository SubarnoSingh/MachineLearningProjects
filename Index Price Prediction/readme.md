# 📈 Multiple Linear Regression - Index Price Prediction

This project is a simple implementation of **Multiple Linear Regression** to predict the **Index Price** based on two economic indicators:
- **Unemployment Rate**
- **Interest Rate**

It was built as a basic learning-level machine learning project using a small dataset.

---

## 🧠 Objective

To demonstrate how multiple linear regression can be used to find a relationship between multiple independent variables (interest rate and unemployment rate) and a dependent variable (index price).

---

## 📁 Project Structure


---

## 📊 Dataset Overview

The dataset contains three columns:

| Year | Interest Rate (%) | Unemployment Rate (%) | Index Price |
|------|-------------------|------------------------|-------------|
| 2024 | 3.5               | 4.8                    | 1448.7      |
| 2025 | 3.2               | 4.6                    | 1607.29     |

> 📌 This is a small custom dataset created for educational purposes.

---

## 📌 Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `matplotlib` & `seaborn` for visualization
  - `scikit-learn` for building the regression model

---

## 📈 Model Summary

- Model: **Multiple Linear Regression**
- Features: `Interest Rate`, `Unemployment Rate`
- Target: `Index Price`
- Evaluation: R² score and residual analysis

---

## 🔍 Key Steps

1. Data Loading and Exploration
2. Data Visualization
3. Feature Selection
4. Model Training using `LinearRegression` from scikit-learn
5. Model Evaluation using R² Score
6. Predictions on new input

---

## 🧪 Sample Prediction

```python
# Example
interest_rate = 4.5
unemployment_rate = 5.0

predicted_index_price = model.predict([[interest_rate, unemployment_rate]])
print(predicted_index_price)
