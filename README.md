# Support-vector-machines

## Regression svm model
The goal is same for now, that is to predict a salary of a potential new employee based on the positions of the previous companies he worked in! But this time, it'll be done using Support vector machines.

## Classification svm model
I've tried doing this with and without scikit learn libraries. Thanks to [Siraj](https://github.com/llSourcell)!
Loss function and objective function have been used for minimizations and optimizations respectively.

## Loss Function
Hinge loss function is being used here for training classifiers. The hinge loss is used for "maximum-margin" classifications, most notably for SVMs.

## Objective Function
Objective of SVM consists of two terms. The first term is a regularizer, and the second term is the loss. The regularizer balances between margin maximization and loss. We want to find the decision surface that is maximally far away from any data points. We're going to use gradient descent to optimize the model. 

## Initial Plot of 5 samples
Classification of 2 datasets by a possible hyperplane. It's obviously not the ideal one, but I'll try to find the optimal hyperplane by minimizing the error function using gradient descent. 
![alt text](https://i.imgur.com/JtRyqTq.png)

## Plotting 2 test samples based on trained data
'+' in red and '-' in blue.
![alt text](https://i.imgur.com/U8vVsym.png)

## Combining the above plots for a better visualization
I added those 2 test samples. Plotted the hyperplane, the discriminator, that's trained on the training data and it classifies the training data and testing data precisely. Such that they all end up in the right side of the decision boundary so that they are correctly classified. '+' on one side and '-' on the other side.
![alt text](https://i.imgur.com/QDP9mAD.png)
