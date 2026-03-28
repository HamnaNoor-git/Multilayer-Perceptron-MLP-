
# MVC Project: Multilayer Perceptron (MLP)
**Overview**
This project implements a Multilayer Perceptron (MLP) from scratch using NumPy. The implementation follows the complete neural network pipeline including forward propagation, loss computation, backpropagation, and gradient descent optimization.

The model is trained on the MNIST dataset to classify handwritten digits (0–9).


## Network Architecture
* Input Layer: 784 neurons (28×28 pixels)
* Hidden Layer 1: 128 neurons (Sigmoid)
* Hidden Layer 2: 64 neurons (Sigmoid)
* Output Layer: 10 neurons (Sigmoid)


## Features Implemented
* Sigmoid activation function and its derivative
* Forward propagation
* Mean Squared Error (MSE) loss
* Backpropagation using chain rule
* Gradient Descent weight updates
* Mini-batch Gradient Descent (batch size = 32)
* Training loop with shuffled data
* Loss curve visualization
* Test accuracy evaluation
* Sample predictions display


##  Results
* The loss decreases over epochs, showing successful learning.
* The model achieves reasonable accuracy on the MNIST test dataset.
* Predictions improve as training progresses.

## Output
* Training loss curve
* Test accuracy percentage
* Sample predictions on test images

---

## Notes
* All computations are implemented manually using NumPy.
* No deep learning frameworks (e.g., PyTorch/TensorFlow) are used for training.
* The implementation strictly follows the project tasks (Task 1–7).

---

##  Author
Name: Hamna Noor
Roll No: 25i-3113
FAST NUCES, Islamabad

## Conclusion
This project builds a complete understanding of neural networks from scratch, including how forward pass, backpropagation, and optimization work together to train a model.

