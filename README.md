# EN3150 - Pattern Recognition Assignment 01

## Overview
This repository contains the implementation and analysis for **Assignment 01** of the EN3150 Pattern Recognition course, University of Moratuwa.  
The assignment covers regression, robust loss functions, and data preprocessing.

## Contents
1. **Task 1: Linear Regression Impact on Outliers**
   - Fit linear regression model to dataset
   - Compare reference and learned models
   - Apply robust loss function to mitigate outliers
   - Evaluate models with different β values

2. **Task 2: Loss Function Comparison**
   - Compare Mean Squared Error (MSE) and Binary Cross Entropy (BCE)
   - Evaluate performance for continuous vs binary applications
   - Justify appropriate loss function selection

3. **Task 3: Data Pre-processing**
   - Generate sparse and noisy feature signals
   - Apply scaling methods: Standard, Min-Max, and Max-Abs
   - Select appropriate scaling preserving feature properties

## Key Findings
- Robust loss with **β = 1** balances sensitivity and outlier suppression.
- **Model 1** outperforms Model 2 under robust evaluation.
- **MSE** is optimal for regression with continuous targets.
- **BCE** is suitable for binary classification tasks.
- **Max-Abs scaling** preserves sparsity for sparse signals.
- **Standard scaling** optimizes Gaussian-distributed features.

## Repository Structure
