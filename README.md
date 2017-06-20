# Introduction
Before we dive into neural networks, let's have a broader perspective.

## AI vs ML vs DL
**Artificial Intelligence** is about simulation of human intelligence by machines to perform task thats required human intelligence. **Machine Learning** is a branch of AI that instead of based on human coded rules, machine perform tasks by learning itself based on massive data that being feed into it. **Deep Learning** is a way of machine learning that added with hidden layers of nodes in between input and output data, that are able to tweak and adjust to produce optimum result.

![AI vs ML vs DL](/images/chart01.png)

## What is a neural network?
An **Artificial Neural Network** is about mimicking the way human's brain works, by transmitting signals from nodes to nodes  These nodes are fully connected, with every node in one layer connected to every other node in next layer.

We are going to touch on the simplest model, by passing the signals from front to back, called **feedforward**, to predict an output and later use a backwards process called **backpropagation** to learn by adjusting the nodes in order to achieve better accuracy.

![Feedforward model](/images/feedforward.png)

## Components
 * input nodes
 * hidden nodes
 * output nodes
 * weights

Every single neuron will go through a calculation process.
  1. Input signals **multiply** with corresponding **weights**.
  2. Outcome of the multiplication will be **summed** up. (Optional) *Bias* may or may not added to the sum.
  3. Activation.

![A neuron](/images/neuron.png)

![A 'deeper' feedforward example](/images/simple_nn.png)

## Activation function

## Loss/Cost

## Backpropagation
