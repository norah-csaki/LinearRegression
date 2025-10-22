# Linear and Ridge Regression

This notebook demonstrates the difference between Ordinary Least Squares (OLS) and Ridge regression using synthetic data.  
It shows how regularization (α) affects model complexity and the bias–variance tradeoff.

## Preview
![Ridge Comparison](ridge_comparison.png)

## Highlights
- Fits OLS and Ridge models using scikit-learn
- Implements a custom Linear Regression class (normal equation)
- Compares regression lines for different α values
- Illustrates how Ridge smooths the fit and reduces overfitting

## How to Run
Install dependencies and open the notebook:
```bash
pip install numpy pandas matplotlib scikit-learn
jupyter notebook LinearRegression.ipynb
