- Telecom Customer Churn identification is a unique case study where we calculate if a user will churn or not based on various personal and usage details of the user with the company.

Deep Learning concepts used: 
- Dropouts: Dropout is a regularization method that tries to minimize the effect of ovefitting. Here particular node in a layer is randomly dropped out thus making a look alike layer with no dropped out nodes of the hidden layer. Nodes are dropped out randomly and allows algorithm to learn by giving opportunity to all nodes.

- Callbacks: Callbacks are methods called after execution of each epoch. They are primarily used to monitor the algorithm run and store necessary variables. Two callback functions used here are: Early stopping callback: This monitors the given variable to check if there is no change in the value of variable over a given time (patience) and asks the algortihm to stop processing further. This reduces the processing time. Model Checkpoint: Here the model with best monitor variable value is stored in a file which can be used later to get the best result.

- Regularization: To avoid overfitting, regularization is used to avoid algorithm to learn completely from the training data and have very low validation accuracy or high validation loss. Essentially system restricts blowing up of parameters during training the algorithm.
