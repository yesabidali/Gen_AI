# What is Aritifical Neural Network?

Various nodes group together and form ANN. It is inspired by working human brain it have nodes like NN have neural. It work similar as NN used to process the infomation it is designed to recognize patterns and solve complex problems

## Basic terminology that helps us to understand working of ANN

- Neuron : It is smallest unit or we can say building block of ANN which takes input, process it and produce output
- Weight : It adjust which input is more important and which is less important
- Bias : The neuron adds a bias, which is like an extra adjustment
- Activation function: Number that is present in neuron is their activation function it decide how output is strong or weak the if AF is toward 1 then output is strong if it is towards 0 then its weak

## Now understand the working of ANN?

Aritifical Neural Network is consists of Input layer, hidden layer, output layer

- Input layer: It's takes the input like picture of Tiger before sending input to hidden layer each neuron is multiple weights which help to tell which feature is more important and add some bias to adjust it more or to shift result
(z=w×x+b) after that output pass through activation function, which decides whether the Activation of neuron

- Hidden layer: There is multiple hidden layer which process the data. It identify the stucture and pattern

- Output Layer: This is final layer and give output

## How neural network train?

Before understanding training of neural network we have to understand the basic terminology that used in traning of neural network

- Forward propagation: Which means data is travel from input layer then hidden layer and finally outpuct layer

- Loss function: It tell how wrong the pridiction is compare to actuall output or we can can say diffrent between predicted output and actual output is loss function.
Mean Squared Error (MSE)  For Regression
Cross-Entropy Loss For Classification

- Backpropagation: In this network goes backward to fix weight and bias. Its goal is to reduce the difference between the model’s predicted output and the actual output by adjusting the weights and biases in the network

- Gradient decent: It is a technique that find bias and weight that produce lowest loss. The lower the loss the high prediction is.

## How neural network is traing?

1) Forward Propagation (Making Predictions)
The input data flows through the network.
Each neuron applies weights, bias, and an activation function to generate an output

2) Loss Function (Measure the Error)
The loss function calculates how wrong the prediction is
Example Loss Functions:
Mean Squared Error (MSE) : For Regression
Cross-Entropy Loss : For Classification

3) Backpropagation (Fix the Mistakes)
The network goes backward to find which weights and biases caused the error.
It calculates the gradient (derivative) of the loss function with respect to each weight.

4) Gradient Descent (Update Weights and Biases)
We update the weights and biases to reduce the error

5) Repeat the Process
The network keeps repeating the process for multiple times until the loss is minimized and the network learns the pattern  
