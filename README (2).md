A. Build a baseline model

Use the Keras library to build a neural network with the following:

One hidden layer of 10 nodes, and a ReLU activation function

Use the adam optimizer and the mean squared error as the loss function.

Randomly split the data into a training and test sets by holding 30% of the data for testing. You can use the "train_test_split" helper function from "Scikit-learn". 
Train the model on the training data using 50 epochs.

Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength. You can use the mean_squared_error function from Scikit-learn.

Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.

B. Normalize the data

Repeat Part A but use a normalized version of the data. Recall that one way to normalize the data is by subtracting the mean from the individual predictors and dividing by the standard deviation.

C.Increate the number of epochs

Repeat Part B but use 100 epochs this time for training.

D.Increase the number of hidden layers

Repeat part B but use a neural network with the following instead:

Three hidden layers, each of 10 nodes and ReLU activation function.
