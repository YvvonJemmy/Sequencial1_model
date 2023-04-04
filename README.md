# Sequential_model
This is a simple sequential model using tensorflow.
This project trains a sequential model using the TensorFlow and Keras libraries to classify handwritten numbers using the MNIST dataset. The MNIST dataset consists of 60,000 training examples and 10,000 test examples, each of which is a 28x28 pixel grayscale image of a handwritten digit with its associated label.

# Installation
To run this project, you will need to have the following packages installed:
- TensorFlow
- Keras
- numpy
- matplotlib

# Dataset
There is no need to directly download the MNIST dataset because it is a part of the Keras library.

# Architecture of model
Three levels make up the sequential model:

- The 28x28 pixel picture is flattened into a 1D array of 784 pixels using this layer.
- Dense layer: This layer employs the ReLU activation function and has 128 neurons.
- The output layer employs the softmax activation function to generate a probability distribution over the 10 classes. It has 10 neurons (one for each possible digit).
The Adam optimizer and categorical crossentropy loss are used to build the model, which is then trained for 10 epochs with a 32-person sample size.

# Result
After training the model for 10 epochs, the model achieved an accuracy of 98.27% on the test set.

