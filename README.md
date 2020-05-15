# Learning Representations by Recirculation

Reproducing the results of "Learning Representations by Recirculation" (Hinton &amp; McClelland, 1988), presented at Neural Information Processing Systems, 1988, pages 358-366.

This Jupyter Notebook aims to reproduce the type of neural network outlined in this paper and the results of a simulation. The key interesting point of this paper is that the network weights are trained not via backpropagation, but instead by comparing the difference to an input vector after it is recirculated through the network.

The network is comprised of an input ("visible") layer with 4 neurons, fully connected to a hidden layer of 2 neurons, fully connected to the "visible" layer in a closed loop. The network aims to reconstruct the input vector from the hidden layer.

The idea behind this network is similar to that of an autoencoders.
