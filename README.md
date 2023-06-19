# Basic neural network from scratch

This repository contains a basic neural network implemented from scratch in Python, without the use of any external libraries such as numpy. The main purpose of this project is to gain a deeper understanding of how neural networks work by building one from the ground up. While the network may not be as efficient as those implemented using specialized libraries, it serves as an educational tool for exploring the fundamental concepts behind neural networks.

## Features
* Supports Sigmoid and ReLu activations.
* Utilizes stochastic gradient descent for the learning process.
* Offers the flexibility to choose a custom learning rate (eta) and momentum.

## Example: Logical operators
The repository includes an example scenario where the network is trained to perform logical operations. The inputs provided to the network consist of 6 bytes: the first four bytes represent a logical operator, such as disjunction, conjunction, xor, nor, etc. The last two bytes represent the operands p and q. The goal is for the network to predict the output of the logical operation, which will always be 0 or 1.

The example demonstrates how the network can learn and make predictions based on given inputs. The output layer of the network consists of a single neuron using a sigmoid activation, while the hidden layers utilize the ReLU activation. You can explore and modify this example to gain insights into how the network handles different logical operations.
