Implementing Gradient Descent
In the following notebook, you'll be able to implement the gradient descent algorithm on the following sample dataset with two classes.


Red and blue data points with some overlap.

Workspace
To open this notebook, you have two options:

Go to the next page in the classroom (recommended)
Clone the repo from Github and open the notebook GradientDescent.ipynb in the intro-neural-networks > gradient-descent folder. You can either download the repository via the command line with git clone https://github.com/udacity/deep-learning-v2-pytorch.git, or download it as an archive file from this link.
Instructions
In this notebook, you'll be implementing the functions that build the gradient descent algorithm, namely:

sigmoid: The sigmoid activation function.
output_formula: The formula for the prediction.
error_formula: The formula for the error at a point.
update_weights: The function that updates the parameters with one gradient descent step.
When you implement them, run the train function and this will graph the several of the lines that are drawn in successive gradient descent steps. It will also graph the error function, and you can see it decreasing as the number of epochs grows.