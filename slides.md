---
theme: apple-basic
---

# Linear Regression in Machine Learning

Regression Analysis: Predicting Continuous Values

---

# Overview of Linear Regression

Linear Regression is a fundamental algorithm in Machine Learning that predicts a continuous output variable based on one or more input features.

---

# Key Concepts

* **Dependent Variable (Target Variable)**: The variable we want to predict
* **Independent Variables (Features)**: The variables used to make predictions
* **Coefficients (Weights)**: The learned parameters that define the relationship between features and the target variable

---

# The Linear Regression Equation

**y = β0 + β1x + ε**

* **y**: Dependent variable
* **x**: Independent variable
* **β0**: Intercept or bias term
* **β1**: Slope coefficient
* **ε**: Error term

---

# How Linear Regression Works

* The goal is to find the best-fitting line that minimizes the error between predicted and actual values
* The line is defined by the coefficients (β0 and β1) that are learned during training

---

# Model Training Process

* **Cost Function**: Measures the difference between predicted and actual values (e.g., Mean Squared Error)
* **Gradient Descent**: An optimization algorithm used to minimize the cost function and find the best coefficients

```python
# Gradient Descent Example
while True:
  # Compute gradients
  gradient_beta0 = ...
  gradient_beta1 = ...

  # Update coefficients
  beta0 = beta0 - learning_rate * gradient_beta0
  beta1 = beta1 - learning_rate * gradient_beta1

  # Check for convergence
  if converge:
    break
```

---

# Evaluation Metrics

* **Root Mean Squared Error (RMSE)**: Measures the average distance between predicted and actual values
* **R² Score (Coefficient of Determination)**: Measures the proportion of variance in the target variable that is predictable from the feature(s)

---

# Use Cases and Limitations

* **Use Cases**: Predicting continuous values (e.g., stock prices, energy consumption)
* **Limitations**: Assumes a linear relationship, sensitive to outliers and noise

---

# Examples and Visualizations

* **Simple Regression**: Predicting house prices based on the number of bedrooms
* **Multiple Regression**: Predicting energy consumption based on temperature and humidity

```python
import matplotlib.pyplot as plt

# Scatter plot of house prices vs. number of bedrooms
plt.scatter(x, y)
plt.xlabel("Number of Bedrooms")
plt.ylabel("House Price")
plt.title("Simple Regression Example")
plt.show()
```

---

# Conclusion

Linear Regression is a powerful algorithm for predicting continuous values in machine learning. By understanding the key concepts, equation, and evaluation metrics, we can build and evaluate effective linear regression models.

---

# Q&A

Do you have any questions about linear regression in machine learning?