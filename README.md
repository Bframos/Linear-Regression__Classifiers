# Linear Regression (From Scratch)

This repository contains a Jupyter Notebook that implements **Linear Regression** from scratch without using high-level machine learning libraries like Scikit-Learn. It demonstrates the mathematical foundations of finding the best-fitting line for a collection of points in $\mathbb{R}^2$.

## 📝 Project Overview

We aim to optimize the parameters:
* **$w$ (Weight)**
* **$b$ (Bias)**

1.  **Data Generation**: Creating a synthetic dataset for testing.
2.  **Model Definition**: Implementing the linear function $f(x) = wx + b$.
3.  **Gradient Descent**: Manually calculating gradients ($\frac{\partial L}{\partial w}, \frac{\partial L}{\partial b}$) to update parameters.
4.  **Training Loop**: Running the optimization over 10,000 epochs.

## 📊 Results & Visualizations

### 1. Model Fit
The red line represents the learned model ($y = wx + b$) fitting the blue data points.

![Linear Regression Fit](linear_fit.png)
*(Note: Replace `linear_fit.png` with your actual plot file)*

### 2. Learning Curve (Loss over Time)
This graph shows how the error (Loss) decreases as the training epochs progress, indicating that the model is learning.

![Loss History](loss_curve.png)
*(Note: Replace `loss_curve.png` with your actual loss plot file)*

