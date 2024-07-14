# Concrete Compressive Strength Prediction

## Overview

This project focuses on predicting Concrete Compressive Strength using Machine Learning techniques, specifically Linear Regression with Least Squares Method and Gradient Descent Algorithms. The dataset used comprises 1030 observations with 8 input variables and 1 output variable (Compressive Strength in MPa). The dataset is included in the repository with description.

## Methodology

- **Data Preprocessing**: 
  - Duplicate removal and outlier handling using Inter-quartile Range (IQR) based Capping.
  - Box-Cox transformation for normality of data.

- **Model Training**:
  - Implemented custom Linear Regression and Gradient Descent algorithms.

**Assumptions Verification**:
  - Verified assumptions such as linearity, normality, and homoscedasticity.
  - Assessed multicollinearity using correlation matrices and variance inflation factors (VIF).

## Results

- **Performance Metrics**:
  - Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 score were computed.
  - Both Least Squares method and Batch Gradient Descent consistently achieved an R2 score of 0.8335.

## Conclusion

This project successfully utilized Linear Regression to predict Concrete Compressive Strength, demonstrating robust performance despite non-linear interactions among features. Assumptions associated with Linear Regression were thoroughly validated, providing valuable insights for optimizing concrete mixtures in Civil Engineering applications.

## Why This Project?

Understanding Concrete Compressive Strength is crucial in Civil Engineering for ensuring structural integrity and durability of constructions. Machine Learning models can assist in predicting and optimizing concrete properties, thereby enhancing construction practices and material efficiency.
