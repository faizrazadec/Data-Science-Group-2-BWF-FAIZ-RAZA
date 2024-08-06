## Neural Networks Basics: Perceptron and Activation Functions 🧠

### Overview 📋

Neural networks, inspired by the human brain, consist of interconnected layers of neurons. This task involved creating a simple neural network from scratch for a regression task. The main components include perceptrons, activation functions, mean squared error (MSE) for measuring prediction accuracy, and gradient descent for optimizing the model's weights.

### Key Concepts ⚙️

1. **Perceptron**:
   - The simplest neural network that uses a weighted sum of inputs and an activation function to produce an output. 🧩

2. **Activation Functions**:
   - **Sigmoid**: Produces outputs between 0 and 1, useful for binary classification. 📉
   - **ReLU (Rectified Linear Unit)**: Introduces non-linearity, allowing the network to learn complex patterns by outputting the input directly if positive, otherwise, it outputs zero. 📈

3. **Mean Squared Error (MSE)**:
   - Measures the accuracy of predictions by calculating the average of the squared differences between predicted and actual values. 📏

4. **Gradient Descent**:
   - An optimization algorithm that adjusts the model's weights to minimize the MSE by iteratively moving towards the steepest descent. 🔄

### Simple Neural Network Implementation 🧩

A basic neural network was created with the following structure:
- **Input Layer**: Takes the input features.
- **Hidden Layer**: Applies weights, bias, and activation function to learn from the input data.
- **Output Layer**: Produces the final prediction for the regression task.

### Process 🛠️

1. **Initialize Weights and Biases**: Randomly initialize weights and biases for the input and hidden layers.
2. **Forward Propagation**: Calculate the weighted sum of inputs and apply the activation function.
3. **Compute Loss**: Use MSE to calculate the difference between predicted and actual values.
4. **Backward Propagation**: Adjust weights and biases using gradient descent to minimize the MSE.
5. **Iteration**: Repeat the forward and backward propagation steps until the model converges to a minimum error.

---
