# Classification Algorithms using scikit-learn

## Objective
The goal of this task is to explore and implement various classification algorithms using scikit-learn, a popular machine learning library in Python. These algorithms are used to categorize data into predefined classes, and each has its strengths and use cases.

## Classification Algorithms

### 1. Logistic Regression
Logistic Regression models the probability of a binary outcome using the logistic function. It's commonly used for binary classification tasks, where the output is a probability value between 0 and 1. The model uses the following logistic function:

\[ P(Y=1) = \frac{1}{1 + e^{-(\beta_0 + \beta_1X_1 + \beta_2X_2 + ... + \beta_nX_n)}} \]

### 2. k-Nearest Neighbors (k-NN)
k-NN classifies data based on the majority class of its nearest neighbors. It is a simple, instance-based learning method where classification is deferred until a prediction is required. The algorithm calculates the distance between the test point and all training points, selecting the k-nearest neighbors and assigning the majority class:

- **Distance Metrics**: Euclidean, Manhattan, Minkowski, etc.
- **Parameter**: k (number of neighbors)

### 3. Support Vector Machines (SVM)
SVMs find the optimal hyperplane that separates classes with the maximum margin. This algorithm is effective in high-dimensional spaces and is versatile, allowing for different kernel functions (linear, polynomial, radial basis function, etc.):

- **Kernel Functions**: Linear, Polynomial, RBF, Sigmoid
- **Parameters**: C (regularization parameter), gamma (kernel coefficient)

### 4. Decision Trees
Decision Trees split data into subsets based on feature values to make decisions. The model is interpretable and easy to visualize. Each internal node represents a "test" on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label:

- **Criteria**: Gini impurity, Information gain (entropy)
- **Parameters**: Max depth, Min samples split, Min samples leaf

### 5. Random Forests
Random Forests are an ensemble of decision trees that improve classification accuracy by averaging the predictions of multiple trees. They reduce overfitting by using random subsets of features and data samples:

- **Number of Trees**: n_estimators
- **Criteria**: Gini impurity, Information gain (entropy)
- **Parameters**: Max depth, Min samples split, Min samples leaf, Max features

### 6. Gradient Boosting
Gradient Boosting builds models sequentially, with each new model correcting errors of the previous ones. It is a powerful technique for both classification and regression tasks and includes variants like Gradient Boosted Trees, XGBoost, LightGBM, and CatBoost:

- **Learning Rate**: Controls the contribution of each tree
- **Number of Estimators**: The number of boosting stages
- **Max Depth**: The maximum depth of each tree

### 7. Naive Bayes
Naive Bayes applies Bayes' theorem with an assumption of feature independence to classify data. Despite its simplicity, it performs well on various tasks, especially text classification and spam detection:

- **Types**: Gaussian, Multinomial, Bernoulli
- **Assumption**: Independence among features
