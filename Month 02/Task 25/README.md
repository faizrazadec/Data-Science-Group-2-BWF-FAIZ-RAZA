# Logistic Regression from Scratch

## Objective
The goal of this task is to implement Logistic Regression from scratch, without using built-in libraries. This exercise aims to deepen understanding of the core mechanics behind logistic regression, including the sigmoid function, cost function, and optimization techniques like gradient descent.

## Components of Logistic Regression

### 1. Sigmoid Function
The sigmoid function is used in logistic regression to model the probability of a binary outcome. It maps any real-valued number to a value between 0 and 1. The sigmoid function is defined as:

$[ \sigma(z) = \frac{1}{1 + e^{-z}} $]

where $( z = \beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_nx_n $) represents the linear combination of input features and weights.

### 2. Cost Function
The cost function measures the error between the predicted probabilities and the actual labels. For logistic regression, the cross-entropy loss (also known as log loss) is commonly used:

$[ J(\beta) = -\frac{1}{m} \sum_{i=1}^{m} \left[ y_i \log(h_\beta(x_i)) + (1 - y_i) \log(1 - h_\beta(x_i)) \right] $]

where:
- $( m $) is the number of training examples
- $( y_i $) is the actual label of the $( i $)-th training example
- $( h_\beta(x_i) $) is the predicted probability for the $( i $)-th training example

### 3. Gradient Descent
Gradient descent is an optimization algorithm used to minimize the cost function by iteratively adjusting the model weights. The weight update rule is:

$[ \beta_j := \beta_j - \alpha \frac{\partial J(\beta)}{\partial \beta_j} $]

where:
- $( \alpha $) is the learning rate
- $( \frac{\partial J(\beta)}{\partial \beta_j} $) is the partial derivative of the cost function with respect to the weight $( \beta_j $)

## Implementation Steps

### Step 1: Initialize Parameters
Initialize the weights and bias to zeros or small random values.

### Step 2: Define the Sigmoid Function
Implement the sigmoid function to compute the probabilities.
