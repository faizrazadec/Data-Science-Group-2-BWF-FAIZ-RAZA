# Linear Regression from Scratch 🚀

Creating Linear Regression from scratch involves several key steps. Here's a breakdown of the process:

## 1. Initializing Parameters 🎯

- **Weights (w)**: The coefficients that will be multiplied with the features.
- **Bias (b)**: The constant term added to the weighted sum of features.

## 2. Hypothesis Function 📈

The hypothesis function for Linear Regression is defined as:

\[ \hat{y} = w \cdot x + b \]

Where:
- \( \hat{y} \) is the predicted value.
- \( x \) is the input feature.
- \( w \) is the weight.
- \( b \) is the bias.

## 3. Loss Function 📉

To measure the performance of the model, we use the Mean Squared Error (MSE) as our loss function:

\[ \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (\hat{y}_i - y_i)^2 \]

Where:
- \( \hat{y}_i \) is the predicted value for the \(i\)-th data point.
- \( y_i \) is the actual value for the \(i\)-th data point.
- \( n \) is the number of data points.

## 4. Optimization with Gradient Descent 🏃‍♂️

Gradient Descent is used to minimize the loss function by iteratively updating the parameters:

1. **Compute Gradients**: Calculate the gradient of the loss function with respect to the weights and bias.
2. **Update Parameters**: Adjust the weights and bias in the direction that reduces the loss function.

The update rules are:

\[ w = w - \alpha \frac{\partial \text{MSE}}{\partial w} \]
\[ b = b - \alpha \frac{\partial \text{MSE}}{\partial b} \]

Where:
- \( \alpha \) is the learning rate.
- \(\frac{\partial \text{MSE}}{\partial w}\) and \(\frac{\partial \text{MSE}}{\partial b}\) are the gradients of the MSE with respect to \( w \) and \( b \), respectively.

## 5. Iterative Process 🔄

Repeat the gradient descent steps until the loss function converges to a minimum value, indicating that the model's parameters are optimized.

## Conclusion 🎉

Understanding these steps helps in grasping the fundamental mechanics of Linear Regression and how predictions are refined through optimization.

Feel free to tweak and experiment with the parameters to see how the model's performance changes!

