# Evaluation Techniques for Regression Models 📊

Evaluating regression models is essential for understanding their performance and effectiveness. Various metrics provide insights into different aspects of model accuracy and error. Here’s an overview of common evaluation techniques used to assess regression models.

## 1. Mean Absolute Error (MAE) 📉

### Overview
MAE measures the average magnitude of errors in a set of predictions, without considering their direction. It provides a straightforward metric for the model's prediction accuracy.

### Formula
\[ \text{MAE} = \frac{1}{n} \sum_{i=1}^{n} | \hat{y}_i - y_i | \]

Where:
- \( \hat{y}_i \) is the predicted value.
- \( y_i \) is the actual value.
- \( n \) is the number of data points.

## 2. Mean Squared Error (MSE) 📏

### Overview
MSE calculates the average of the squared differences between predicted and actual values. It emphasizes larger errors due to squaring the differences, making it sensitive to outliers.

### Formula
\[ \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (\hat{y}_i - y_i)^2 \]

## 3. Root Mean Squared Error (RMSE) 🌟

### Overview
RMSE is the square root of MSE, providing error estimates in the same unit as the target variable. It offers a more interpretable measure of prediction accuracy compared to MSE.

### Formula
\[ \text{RMSE} = \sqrt{\text{MSE}} \]

## 4. R-squared (R²) 📐

### Overview
R-squared indicates the proportion of variance in the dependent variable that is predictable from the independent variables. It measures how well the model explains the variability of the target variable.

### Formula
\[ R^2 = 1 - \frac{\text{SS}_{\text{res}}}{\text{SS}_{\text{tot}}} \]

Where:
- \( \text{SS}_{\text{res}} \) is the sum of squared residuals.
- \( \text{SS}_{\text{tot}} \) is the total sum of squares.

## 5. Adjusted R-squared 📏

### Overview
Adjusted R-squared adjusts the R-squared value for the number of predictors in the model, providing a more accurate measure when comparing models with different numbers of predictors.

### Formula
\[ \text{Adjusted } R^2 = 1 - \left( \frac{1 - R^2}{n - k - 1} \right) \times (n - 1) \]

Where:
- \( n \) is the number of observations.
- \( k \) is the number of predictors.

## 6. Mean Absolute Percentage Error (MAPE) 📊

### Overview
MAPE expresses prediction accuracy as a percentage, providing an intuitive measure of how well the model performs relative to the size of the target variable.

### Formula
\[ \text{MAPE} = \frac{1}{n} \sum_{i=1}^{n} \left| \frac{\hat{y}_i - y_i}{y_i} \right| \times 100\% \]

## 7. Median Absolute Error 🧮

### Overview
Median Absolute Error measures the median of the absolute errors, offering a robust measure of central tendency that is less sensitive to outliers compared to MAE.

### Formula
\[ \text{Median Absolute Error} = \text{median} \left( | \hat{y}_i - y_i | \right) \]

## Conclusion 🎉

These evaluation metrics are crucial for comparing and refining regression models. Each metric provides different insights into the model's performance, helping to choose the most appropriate model for a given task.
