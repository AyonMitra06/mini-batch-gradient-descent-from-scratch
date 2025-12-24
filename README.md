# Mini-Batch Gradient Descent from Scratch

This project implements **Mini-Batch Gradient Descent** from scratch using Python and NumPy, without relying on built-in machine learning training methods.

## Overview

- Uses the **Diabetes dataset** from `sklearn`
- All features are **standard scaled**
- Implements linear regression training using **mini-batch gradient descent**
- Compares the learned **coefficients (`coef_`) and intercept** with those obtained from `sklearn.linear_model.LinearRegression`
- Helps understand how optimization works under the hood

## Key Features

- Custom loss function (Mean Squared Error)
- Manual weight and bias updates
- Configurable learning rate, batch size, and epochs
- Side-by-side comparison with scikit-learn’s LinearRegression

## Tech Stack

- Python
- NumPy
- scikit-learn (for dataset, scaling, and comparison model)

## Purpose

This repository is intended for **learning and experimentation**, making it easier to understand how gradient descent optimizes linear regression models internally.

## Dataset

- **Diabetes Dataset** from `sklearn.datasets`
- Features are **standardized** using `StandardScaler` before training

## Results

The final coefficients and intercept from the custom implementation closely match those from `sklearn`’s `LinearRegression`, validating the correctness of the implementation.

---