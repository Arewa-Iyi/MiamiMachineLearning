# Details
The purpose of this program is to create a dataset containing the interval of 100,000 - 999,999 
along with the boolean of its attributes in order to train a neural network for classification.

After the data set has been created, a model is created with a Sequential object imported from 
tensorflow.keras.models containing Dense layers with a sigmoid activation. 
The data set is split into training and test sets, then normalized and the model is trained 
using the training set. Upon completion of training, we predict our output 
values usingthe model.predict() function.

The Accuracy, Confusion Matrix, and Classification Report are there printed to screen.
