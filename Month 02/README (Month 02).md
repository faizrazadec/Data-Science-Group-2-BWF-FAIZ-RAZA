[# Task 18: Introduction to Seaborn - Visualization with Seaborn 📊](https://github.com/faizrazadec/Data-Science-Group-2-BWF-FAIZ-RAZA/tree/main/Month%2002/Task%2018)

[# Task 19: Statistical Plotting with Seaborn 📈](https://github.com/faizrazadec/Data-Science-Group-2-BWF-FAIZ-RAZA/tree/main/Month%2002/Task%2019)

[# Task 20: Feature Engineering](https://github.com/faizrazadec/Data-Science-Group-2-BWF-FAIZ-RAZA/tree/main/Month%2002/Task%2020)

Feature engineering is the process of using domain knowledge to select, modify, or create new features (variables) that enhance the performance of machine learning algorithms. It is a critical step in building effective models, as it directly influences their ability to learn and make accurate predictions. 

In this task, we explored various feature engineering techniques through hands-on experience with the Titanic and Iris datasets. The key steps we covered include:

1. **Feature Selection**: Identifying the most relevant features by analyzing their correlation with the target variable and using methods like mutual information or chi-squared tests.
2. **Feature Transformation**: Applying transformations such as log transformation, normalization, and standardization to improve model performance.
3. **Feature Creation**: Creating new features by combining or modifying existing ones to provide more information to the model.
4. **Polynomial Features**: Generating polynomial features to capture non-linear relationships using the `PolynomialFeatures` class from `sklearn.preprocessing`.
5. **Handling Categorical Features**: Converting categorical features into numerical features through encoding techniques like one-hot encoding, label encoding, and target encoding.

Each step was performed using practical examples, demonstrating the importance and impact of feature engineering in machine learning. The transformations and encodings were applied to ensure the models could effectively interpret and utilize the data, leading to improved accuracy and performance.

# Task 21: Linear Algebra and Calculus in NumPy

This document summarizes the completed tasks for the Linear Algebra and Calculus project using NumPy, covering matrix operations, solving linear equations, eigenvalues, vector operations, PCA, numerical differentiation, integration, partial derivatives, and optimization.

## Overview

### Matrix Creation and Manipulation
Created zero, identity, and random matrices. Performed addition, subtraction, and multiplication. Transposed matrices, computed determinants using `np.linalg.det()`, and found inverses using `np.linalg.inv()`.

### Solving Linear Equations
Solved systems of linear equations with `np.linalg.solve()`. Implemented LU decomposition with `scipy.linalg.lu()` and QR decomposition using `np.linalg.qr()`.

### Eigenvalues and Eigenvectors
Calculated eigenvalues and eigenvectors with `np.linalg.eig()` and verified results by reconstructing the original matrix.

### Vector Operations
Executed vector operations: addition, dot product (`np.dot()`), and cross product (`np.cross()`). Normalized vectors and computed norms using `np.linalg.norm()`.

### Matrix Decomposition
Applied Principal Component Analysis (PCA) using Singular Value Decomposition (SVD) via `np.linalg.svd()` for dimensionality reduction.

### Numerical Differentiation
Computed numerical derivatives using forward, backward, and central difference methods to approximate derivatives of functions.

### Numerical Integration
Performed numerical integration using the trapezoidal rule and Simpson's rule to estimate the area under curves.

### Partial Derivatives
Calculated partial derivatives of multivariable functions and verified results against analytical solutions.

### Optimization
Utilized NumPy to solve optimization problems with constraints, finding minimum or maximum values within specified boundaries.

## Conclusion
This project provided a thorough understanding of linear algebra and calculus concepts using NumPy, demonstrating the application of numerical methods and matrix operations essential for various mathematical and engineering applications.
