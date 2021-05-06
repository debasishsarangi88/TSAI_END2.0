# TSAI_END2.0

Assignment:

1.remove the last activation function
 Removed

2. make sure there are in total 44 parameters
self.lin1 = nn.Linear(input_dim, 11,)
self.lin2 = nn.Linear(11, output_dim,bias=False)

Using above tweak to the network 44 parameter is reached.

3.run it for 2001 epochs

Completed



1. What is a neural network neuron?
 Neural network neurons are volatile storage units that stores information.
if it is on input layer then it contains raw input data,if it is in hidden layer
then it has value of previous layer neuron multiplied by weight associated with it and bias added to the final result.
(Considering non-zero bias in the system.)

2. What is the use of the learning rate?
The learning rate controls how quickly the model is trained on the problem. 
Smaller learning rates require more training epochs, since there will be smaller changes made to the weights on each update, 
whereas larger learning rates result in rapid changes and require fewer training epochs.
Genarally learnign rate ranges between 0.0 and 1.0


3. How are weights initialized?
The optimization algorithm used in neural network requires a starting point in the space of possible weight values from which to begin the optimization process. 
Weight initialization is a procedure to set the weights of a neural network to small random values that define the starting point
for the optimization (learning or training) of the neural network model. 
The aim of weight initialization is to prevent layer activation outputs from exploding or vanishing during the course of a forward pass.
Xavier Glorot and Yoshua Bengio came up with a weigth initialization technique which is also known as Xavier/normalized initialization.
Xavier initialization sets a layer’s weights to values chosen from a random uniform distribution that’s bounded between
plus or minus [Sqrt(6)/sqrt(n+(n+1))] where n is number of incoming network connections to the layer and n+1 is the number of outgoing network connections form the layer.
Xavier initializationworks well for networks with Sigmoid/tanh activation functions.
Where as for network with relu activation function kaiming initialization can be used.

4. What is "loss" in a neural network?
loss is the difference between the predicted versus the actual value in the neural network.
There are different types of loss function is used whose objective is to minimize the loss.
Few of the different types of loss functions are :

 Mean Sqauared Error
 Binary cross entropy
 Categorical cross entropy
 Sparse Categorical Cross entropy

Mean Sqauared Error loss is used for regression tasks
Binary cross entropy loss is used for the binary classification tasks.
Categorical cross entropy and Sparse Categorical Cross entropy are used for multi-class classification task.

5. What is the "chain rule" in gradient flow?
The chain rule is used for calculating the derivative of composite functions.
If a variable z depends on the variable y, which itself depends on the variable x, so that y and z are dependent variables, then z,
via the intermediate variable of y, depends on x as well. This is called the chain rule.
