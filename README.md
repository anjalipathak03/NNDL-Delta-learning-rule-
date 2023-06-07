# Delta learning rule
The delta rule is a formula for updating the weights of a neural network during training. It is considered a special case of the backpropagation algorithm. The delta rule is in fact a gradient descent learning rule.
Recall that the process of training a neural network involves iterating over the following steps:

A set of input and output sample pairs are selected randomly and run through the neural network. The network makes predictions on these samples.

The loss between the predictions and the true values is computed.

Adjust the weights in a direction that makes the loss smaller.

The delta rule is one algorithm that can be used repeatedly during training to modify the network weights to reduce loss error.

It is based on a gradient descent approach which continues forever. It states that the modification in the weight of a node is equal to the product of the error and the input where the error is the difference between desired and actual output.

The delta rule in an artificial neural network is a specific kind of backpropagation that assists in refining the machine learning/artificial intelligence network, making associations among input and outputs with different layers of artificial neurons. 

Generally, backpropagation has to do with recalculating input weights for artificial neurons utilizing a gradient technique. Delta learning does this by using the difference between a target activation and an obtained activation. By using a linear activation function, network connections are balanced. Another approach to explain the Delta rule is that it uses an error function to perform gradient descent learning.

Application


The generalized delta rule is important in creating useful networks capable of learning complex relations between inputs and outputs. Compared to other early learning rules like the Hebbian learning rule or the Correlation learning rule, the delta rule has the advantage that it is mathematically derived and directly applicable to Supervised Learning. In addition, unlike the Perceptron learning rule which relies on the use of the Heaviside step function as the activation function which means that the derivative does not exist at zero, and is equal to zero elsewhere, the delta rule is applicable to differentiable activation functions like tanh and the sigmoid function

 





