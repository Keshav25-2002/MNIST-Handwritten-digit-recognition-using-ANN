#MNIST Handwritten Digit Recognition using Artificial Neural Networks

This project is a digit recognition system built using Artificial Neural Networks (ANN) to classify handwritten digits from the MNIST dataset.

Dataset

The MNIST dataset is a collection of 70,000 handwritten digits, split into 60,000 training examples and 10,000 test examples.

Model Architecture

The ANN model consists of three dense layers with 784, 256, and 10 nodes respectively. The input layer has 784 nodes to represent the 28x28 pixel input images. The 

hidden layer has 256 nodes, and the output layer has 10 nodes representing the 10 possible digits (0 to 9).

Technology Stack

The following technologies were used to build this project:

Python

Keras

NumPy

Matplotlib

Pandas

Results

The model achieved an accuracy of 97.8% on the test set, which is a good performance for this task. The confusion matrix shows that the model has difficulty in 

distinguishing between certain digits (such as 4 and 9), but performs well overall.

