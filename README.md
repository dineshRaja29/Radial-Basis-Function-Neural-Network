# Radial Basis Function (RBF) Network

## Goal
The goal of this project is to create an alternative to traditional Neural Networks when dealing with data that exhibits radial symmetry rather than linear symmetry. These specialized networks are known as Radial Basis Function (RBF) networks.

## RBF Network
- The Radial Basis Function (RBF) network is an artificial neural network that employs radial basis functions as activation functions.
- The network's output is a linear combination of radial basis functions of the inputs and neuron parameters.
- In this project, we aim to implement the Radial Basis Function (RBF) Network from scratch, as there is no standard implementation in the PyTorch library, to the best of our knowledge.

![RBF Network](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Rbf-network.svg/800px-Rbf-network.svg.png)

## Dataset
The dataset utilized in this project is borrowed from [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_circles.html). It is a toy dataset that consists of a large circle containing a smaller circle in 2D.

## Results

| Sr. No. | Experiment         | #f Intermediate Layers | Training Accuracy | Test Accuracy |
|---------|---------------------|------------------------|-------------------|---------------|
| 1       | Baseline (FF-DNN)   | 2                      | 67.01             | 67.1          |
| 2       | Candidate (RBF)     | 2                      | 97.14             | 97.55         |

## Conclusion
When dealing with data exhibiting radial symmetry, the RBF network outperforms the traditional Feedforward Deep Neural Network (FF-DNN). The RBF network demonstrates superior generalization on the test data compared to FF-DNN in the context of radial symmetry.
