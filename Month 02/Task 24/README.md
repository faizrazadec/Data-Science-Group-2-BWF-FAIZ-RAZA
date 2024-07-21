# Regression Models using scikit-learn 📈

Explore these core regression models provided by `scikit-learn` to predict and analyze your data.

## 1. Linear Regression 📉

### Overview
Models the relationship between a dependent variable and one or more independent variables using a linear function.

### Implementation

```python
from sklearn.linear_model import LinearRegression

# Initialize and fit the model
model = LinearRegression()
model.fit(X_train, y_train)

# Make predictions
y_pred = model.predict(X_test)
