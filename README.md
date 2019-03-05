# Udacity-Deep-Learning-Project-1
This is my 1st project on Udacity deep learning Nanodegree by facebook

In this project, I build my first neural network(on this DL Nanodegree course) and use it to predict daily bike rental ridership. 

%matplotlib inline

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is  𝑓(𝑥)=𝑥 . A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called forward propagation.

We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights. This is called backpropagation.

