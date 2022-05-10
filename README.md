# Neural_Network_Charity_Analysis
Preprocessing Data for a Neural Network model and optimizing it

## Overview of the analysis:

During this project, I used the features in the Charaty dataset to create a binary classifier that will tell the customer whether or not the each applicant will be successful using alphabet soup. The dataset contains 34,000+ organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding, etc. This analysis is comprised of 3 parts: 

* Preprocessing the data for the neural network 
* Compiling, training, and evaluating the model 
* Optimizing the model

## Results:

### Data Preprocessing

Variable(s) that are considered the target(s) for your model?

* The variable we are targeting in this module is the 'IS_SUCCESSFUL' column.

Variable(s) that are considered to be the features for your model

* The features that we are using are every column except the ones that we will drop. 

What variable(s) are neither targets nor features were removed 

* The first features we eliminated were the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model

*  This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons; the second has 30. There is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

<img width="1150" alt="Screen Shot 2020-12-06 at 7 36 03 PM" src="https://user-images.githubusercontent.com/67278193/101298129-776e4880-37fa-11eb-9009-3b64f2bb942b.png">

Was the model able to achieve the target model performance?

* Although the target for the model was to be 75% or above, that target was not achieved.

What steps were taken to try and increase model performance?

* Some of the steps taken in attempt to create a more accurate model were: 
    * Adding hidden layers 
    * Changing the activation type
    * Altering the number of epochs 
    * Changing the number of neurons in each layer. 

<img width="1118" alt="adds" src="https://user-images.githubusercontent.com/67278193/101298133-79d0a280-37fa-11eb-9f44-f42358ba1894.png">

## Summary: 

The models accuracy was ~ 72.8% - I began with a data set and attempted to predict whether or not the project would be successful on all of the features that we used after dropping two irrelevant features. Although the accuracy of 75% was not acheived, it is possible the reason for this is that it msy hace been necessary to drop more features (which may have affected how good the neural network actually is). The best way to increase the accuracy of a model is to have more data. If we have solid data added to this model, the accuracy will be much more concrete.
