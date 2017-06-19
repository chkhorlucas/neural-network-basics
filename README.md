# Basics of neural network

![A simple neural network](/images/simple_nn.png)


 input_data | weights | hidden_0_input | hidden_layer_0 | hidden_0_output
:----------:|:-------:|:--------------:|:--------------:|:--------------:
  1  | 2 | 2 | *node_0_0* | 8
  2  | 3 | 6 | *node_0_0* | 8
  1  | 1 | 1 | *node_0_1* | 3
  2  | 1 | 2 | *node_0_1* | 3
  1  | 1 | 1 | *node_0_2* | 1
  2  | 0 | 0 | *node_0_2* | 1


 hidden_0_output | weights | hidden_1_input | hidden_layer_1 | hidden_1_output  
:---------------:|:-------:|:--------------:|:--------------:|:--------------:
  8 | 1 | 8 | *node_1_0* | 5  
  3 | -1 | -3 | *node_1_0* | 5
  1 | 0 | 0 | *node_1_0* | 5
  8 | 0 | 0 | *node_1_1* | 2
  3 | 1 | 3 | *node_1_1* | 2
  1 | -1 | -1 | *node_1_1* | 2
  8 | -1 | -8 | *node_1_2* | 2
  3 | 3 | 9 | *node_1_2* | 2
  1 | 1 | 1 | *node_1_2* | 2


 hidden_1_output | weights | output
:---------------:|:-------:|:-----:
  5 | 2 | 10
  2 | 1 | 2
  2 | 1 | 2


 output |
:------:|
 14 |






## Components
input units, hidden units, output units

## Feedforward

## Activation function

## Loss/Cost

## Backpropagation
