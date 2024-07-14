# Linear Algebra and Calculus in NumPy

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
