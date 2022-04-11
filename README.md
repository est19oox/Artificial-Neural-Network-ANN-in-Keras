# Artificial-Neural-Network-ANN-in-Keras
Predict the attack type (namely, values in the last  column of the data set). Therefore, it is a multiple classification problem. 

# Objectives
(1) Use stratified sampling to get 2/3 data for as training data and 1/3 data as test data.

(2) You can use Scikit-Learn or other Python libraries for pre-processing and stratified sampling. 
However, the ANN must be built with the Keras API in TensorFlow.

(3) The ANN is a Multi-Layer Perceptron where all hidden layers are fully connected (i.e., dense 
layers).

(4) The training process includes a hyperparameter fine-tunning step. Define a grid including at least 
three hyperparameters: (a) the number of hidden layers, (b) the number of neurons in each layer, and 
(c) the regularization parameters for L1 and L2. Each hyperparameter has at least two candidate 
values. All other parameters (e.g., activation functions and learning rates) are up to you.

(5) Return the accuracy of testing

Data set: kddcup.data_10_percent

Source: http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html
