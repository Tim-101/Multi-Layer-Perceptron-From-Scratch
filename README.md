# Multi Layer Perceptron (MLP) From Scratch
This project was created as part of my assignment which was done in a group of three. The project require us to create
an MLP model using only Numpy and Pandas. The input data will not be provided in this repo but it should work with other tabular data.

This MLP model can have multiple hidden layers and activation functions. It was created specifically for multiclass classification task.
Hence, it has Cross Entropy loss function and Softmax activation function. The activation functions and MLP model are created as a saparate class.

Modules that we implemented include:
- Dropout
- Gradient descent with momentum
- ReLU and Softmax activation functions
- Cross Entropy Loss

Our test result showed that the model was able to achieve 83% accuracy in both the train and test data. We also used Confusion Matrix to analyse the model result.
Additionally, the model was able to achieve top 20 accuracy.
