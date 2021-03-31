# Wireless Communications Homework
• Assume a parameter server that is located at the center of a circle area A of 100 meter of radius.
Suppose 10 devices randomly scattered within area (choose random positions of devices within
this circle). Plot the position of the server and the positions of the devices.

• We assume that all devices transmit over the same up-link channel using the same frequency
f = 2GHz. We assume that propagation channels between the devices and the parameter server
are attenuated by a path loss with β = 2 (β is the path loss exponent, the gains of antennas are
assumed equal to 1) and a multipath fading following a Rayleigh distribution of mean µ = 1.
Propose a function (in Python) that computes the channel capacity for each device at each
communication round T. (no multiple access policy is used).

• Assume that devices have access to MNIST dataset. The training set of MNIST is equally devided
between devices ( 6000 image samples to each device). Using a federated learning procedure, each
device i locally trains its dataset Di and sends the gradient descent vector to the central server
for averaging. Due to resource-constrained communications, only a part of the gradient descent
is transmitted using top-K sparsification scheme. Write a function that computes the maximum
K for each channel that can be used for sparsification given a capacity C of the channel. (no
quantization is assumed)

• (Optional) Propose a neural network model (ideally a convolutional neural network model), to
predict the handwritten numbers of MNIST dataset. (Just the structure of the model in terms
of layers and nodes)

• (Optional) Implement the process of federated learning (computation of local gradients at the
devices, sparisification, and averaging). Assume that the sparsified vector is correctly received
at the parameter server. How many iterations are needed for your proposed model to converge.
What is the accuracy of the test using your proposed model?

