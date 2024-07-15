# Three-Layer Neural Network Model
This repository contains a Jupyter Notebook implementing a three-layer neural network from scratch using PyTorch. The notebook walks through the process of setting up the neural network, performing forward propagation, computing the loss using Mean Squared Error (MSE), and updating the weights through backpropagation.

## Description
In this notebook, we construct a neural network with the following architecture:

1 Input Layer: Accepts input features.
2 Hidden Layer: Processes the inputs through a linear transformation followed by an activation function.
3 Output Layer: Outputs the final predictions.

## Key Steps:

-Initialization: Define the network's architecture and initialize weights.
-Forward Propagation: Compute the predictions based on current weights.
-Loss Calculation: Calculate the MSE loss between predictions and actual values.
=Backward Propagation: Compute gradients of the loss with respect to weights.
-Weight Update: Adjust weights using gradients to minimize the loss.

## Code Overview:

-Initialization: We define the weights and activation functions.
-Forward Propagation: Perform matrix multiplication and apply activation functions.
-Loss Function: Use MSE to measure the error.
-Backward Propagation: Calculate gradients using PyTorch's autograd feature.
-Weight Update: Apply gradient descent to update weights iteratively.

## Neural Networks
Neural networks are computational models inspired by the human brain, consisting of interconnected units (neurons) that process information in layers. They are particularly powerful for tasks such as image recognition, natural language processing, and time series prediction.

## Advantages:
-Flexibility: Capable of modeling complex relationships in data.
-Scalability: Suitable for large-scale data.
-Performance: Achieve state-of-the-art results in many applications.

## Advantages of Using PyTorch
PyTorch is a popular deep learning framework that offers several advantages:

-Dynamic Computation Graph: PyTorch builds computation graphs dynamically, making it easier to modify and debug.
-Ease of Use: Intuitive and Pythonic, making it accessible to beginners and researchers.
-Autograd: Automatic differentiation simplifies the implementation of backpropagation.
-Community and Ecosystem: Strong community support with a rich ecosystem of libraries and tools.

## Conclusion
This project demonstrates the fundamental concepts of building and training a neural network using PyTorch. By understanding the basics, you can extend this knowledge to more complex architectures and applications.
