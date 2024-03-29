## Objective
This project aims to build a neural network from scratch, importing as few packages as possible. 

## NN Architecture
To keep the code simple and readable, a small three-layer NN is picked - one input, hidden and output layer.
There are 3 neurons in input layer, 2 neurons in hidden layer and 1 neuron in output layer. 

## Notation
Neurons in input layer are denoted as x1, x2, x3. Weights are denoted by w, biases by b, true value by y, predicted value by y_hat. w1_1 denotes the weight of first edge in first layer. dL_db2_1 denotes partial derivative of L with respect to b2_1 which means the 2nd layer's 1st bias.

## Simplicity and Optimization tradeoff
There are ways to optimize the performance of this program. However, since the target is clarity, code is rather directly translated from math equations without optimization.
