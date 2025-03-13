# Gradient Descent

## Explanation
Gradient descent is an optimization algorithm used to minimize the cost function in machine learning models. It iteratively adjusts the model parameters to find the optimal values that minimize the cost function.

### Importance in Machine Learning
Gradient descent is crucial in training machine learning models, especially in deep learning. It helps in finding the optimal parameters that minimize the error between the predicted and actual values.

### Gradient Descent Algorithms
1. **Batch Gradient Descent**: Uses the entire dataset to compute the gradient and update the parameters.
2. **Stochastic Gradient Descent (SGD)**: Uses a single data point to compute the gradient and update the parameters.
3. **Mini-batch Gradient Descent**: Uses a small batch of data points to compute the gradient and update the parameters.

### Examples
- **Batch Gradient Descent**: If the cost function is J(θ), the parameters are updated as θ = θ - α * ∇J(θ), where α is the learning rate.
- **Stochastic Gradient Descent**: If the cost function is J(θ), the parameters are updated as θ = θ - α * ∇J(θ; x^(i)), where x^(i) is a single data point.
- **Mini-batch Gradient Descent**: If the cost function is J(θ), the parameters are updated as θ = θ - α * ∇J(θ; X^(i)), where X^(i) is a small batch of data points.

## Practice
For practice, refer to the [Gradient Descent Notebook](03_gradient_descent.ipynb).
