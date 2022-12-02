Neural_Network_Charity_Analysis
## Overview of the analysis:
The main purpose of this analysis is using the machine learning ( neural networks) techniques to help the foundation predict where to make investments.
We will use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results:

### Data Preprocessing

* Variable(s) that are considered the target(s) for your model?
The variable we are targeting in this module is the IS_SUCCESSFUL column.

* Variable(s) that are considered to be the features for your model?
Once we drop the non-usable columns, all columns can be considered as features.

* What variable(s) are neither targets nor features were removed?
We dropped the 'EIN' & 'NAME' because these two are not helping to determine our results.

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model?
This model is made with an input features & three hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

* Was the model able to achieve the target model performance?
The model was not able to achieve the target performance of over 75%.

* What steps were taken to try and increase model performance?
Some of the steps I took to try and make the model more accurate were adding hidden layers,changing the number of neurons in each layer, changing the activation type, increasing/decreasing the number of epochs. 

## Summary:
The models accuracy ended up being 72.8% - we started with a data set and tried to predict whether or not the project would be successful on all of the features that we used after dropping two features that we figured to be irrelevant. Although I did not get to the accuracy of 75% that I wanted it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.