# Assignment 09 – Feature Importance & Explainable AI

## Overview

This assignment focuses on **feature importance and model interpretability** for an automotive powertrain and vehicle fuel-consumption use case.

The objective is to understand which features contribute to model predictions and how machine learning models can be interpreted using Explainable AI techniques.

## Objective

- Analyze feature importance using model-based methods.
- Apply permutation feature importance.
- Measure feature relevance using mutual information.
- Visualize feature effects using Partial Dependence Plots.
- Test model behavior in the presence of noisy features.
- Interpret the results from an automotive perspective.

## Techniques Covered

### 1. MDI / Gini Importance

Measures feature importance based on the contribution of features to tree-based model splits.

### 2. Permutation Feature Importance

Measures the change in model performance when individual features are randomly shuffled.

### 3. Mutual Information

Measures the dependency between input features and the target variable.

### 4. Partial Dependence Plots

Visualize how individual features influence model predictions.

### 5. Noise Immunity Testing

Introduces irrelevant or noisy variables to evaluate whether the model can distinguish useful features from noise.

## Domain

**Powertrain Efficiency, Vehicle Fuel Consumption Attribution & Explainable AI**

## Key Concepts

- Feature Selection
- Feature Importance
- Explainable AI
- Model Interpretability
- Mutual Information
- Permutation Importance
- Partial Dependence
- Gradient Boosting

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Notebook

[Assignment 09 – Feature Importance Visualization](./Assignment_09_Feature_Importance_Visualization.ipynb)
