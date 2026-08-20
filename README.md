# Linear Regression using Python

This repository contains simple examples of **Linear Regression using Python and Scikit-learn**.

The project demonstrates both **Simple Linear Regression** and **Multiple Linear Regression** using sample datasets.

##  Topics Covered

* Simple Linear Regression
* Multiple Linear Regression
* Model training using `LinearRegression`
* Coefficients and intercept
* Prediction using a trained regression model

##  Technologies Used

* Python
* NumPy
* Scikit-learn

##  Project Structure

```text
linear-regression-python/
│
├── simple_linear_regression.py
├── multiple_linear_regression.py
└── README.md
```

## 1. Simple Linear Regression

Simple Linear Regression uses **one independent variable** to predict a dependent variable.

Example:

```text
Study Hours → Marks
```

The model is trained using Scikit-learn's `LinearRegression` class.

```python
from sklearn.linear_model import LinearRegression
import numpy as np

X = np.array([[1], [2], [3], [4], [5]])
y = np.array([50, 55, 60, 65, 70])

model = LinearRegression()
model.fit(X, y)

print("Coefficient:", model.coef_[0])
print("Intercept:", model.intercept_)
```

## 2. Multiple Linear Regression

Multiple Linear Regression uses **two or more independent variables** to predict a dependent variable.

Example:

```text
Study Hours + Sleep Hours → Marks
```

It is implemented using the same `LinearRegression` class from Scikit-learn.

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/linear-regression-python.git
```

### 2. Navigate to the project

```bash
cd linear-regression-python
```

### 3. Install required libraries

```bash
pip install numpy scikit-learn
```

### 4. Run the programs

```bash
python simple_linear_regression.py
```

```bash
python multiple_linear_regression.py
```

##  Learning Objective

The purpose of this repository is to understand the basic implementation of **Simple and Multiple Linear Regression using Python and Scikit-learn**.

##  Author

**Aarti Wamane**

