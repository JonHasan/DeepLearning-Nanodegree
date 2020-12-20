# Project 1 Neural Networks - Predicting Bike-Share Patterns

Here is the introduction from the project page

"In this project, you'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! 
By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, 
and other concepts that are important to know before we move to higher level tools such as PyTorch. 
You'll also get to see how to apply these networks to solve real prediction problems!
The data comes from the UCI Machine Learning Database."


This project will test the users ability to create a simple neural net to draw predictions from data.

I had to create a neural network from the ground up and use the gadient descent, backprop etc to get the code to work. 

## Code explanation

### Step 1 : Sigmoid function 

It is first necessary to define the code for the sigmoid function. This will be used to transform any real valued input into a probability. This will determine the chance that a bike needs to be used. The equation is as follows:

\begin{equation}
S = 1/(1+e^-x)
\end{equation}

This was easy to define. There was a choice of using a lambda but I opted for the other option. 


This is the final result 

![image](NeuralNetworkBikeSharing.PNG)

