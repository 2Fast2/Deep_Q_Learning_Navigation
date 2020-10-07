# Project Report
## Model architecture
The architecture is based in the one described in the [provided paper](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf).

We use an architecture in which there is a separate output unit for each possible action, an donly the state is an input to the neural network. The main advantage of this type of architecture is the ability to compute Q-values for all possible actions in a given state with only a single forward pass through the network.

The neural network architecture consists in an two fully connected hidden layers with a ReLU activation function and a fully connected linear output layer:

* Fully connected layer - input: 37 (state size) output: 64 activation : Relu
* Fully connected layer - input: 64 output: 64 activation : Relu
* Fully connected layer - input: 64 output: 4 (action size)

## Training details


