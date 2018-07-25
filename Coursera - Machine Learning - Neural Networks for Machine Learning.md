# Neural Networks for Machine Learning
## What is Machine Learning?
We collect lots of examples that specify the correct output for a given input. A machine learning algorithm then takes these examples and produces a program that does the job.

MNIST database of hand-written digits.

## What are neural networks?
How brain works?
* Each neuron receives inputs from other neurons.
* The effect of each input line on the neuron is controlled
 by a synaptic weight
* The synaptic weights adapt so that the whole network learns to perform useful computations

## Some simple models of neurons
### Linear neurons
![](http://rogercortesi.com/eqn/tempimagedir/eqn7038.png "Exation")

* y is output
* b bias
* x is input
* w is weight

These are simple but computationally limited

### Binary threshold neurons
y = 1 if Linear neuron y >=0, 0 otherwise

### Sigmoid neurons
Smooth values between 0 and 1

### Stochastic binary neurons
Output is probability.

## Types of learning task
* Supervised learning:
Learn to predict an output when given an input vector
* Reinforcement learning:
Learn to select an action to maximize payoff
* Unsupervised learning

##  Types of supervised learning
* Regression: The target output is a real number or a whole vector of
real numbers
* Classification: The target output is a class label

##  Supervised learning
We choose model class: y = f(x; W)
Learning  means adjusting the parameters so that target output fits into y by the model 
