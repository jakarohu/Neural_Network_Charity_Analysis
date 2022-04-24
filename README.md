# Neural Network Charity Analysis
## Overview
With my knowledge of machine learning and neural networks, I will use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, I received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

Using my knowledge of Pandas and the Scikit-Learn’s StandardScaler, I will preprocess the dataset in order to compile, train, and evaluate the neural network model.

Using my knowledge of TensorFlow, I will design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. I will then compile, train, and evaluate my binary classification model to calculate the model’s loss and accuracy.

Finally, using my knowledge of TensorFlow, I will optimize my model in order to achieve a target predictive accuracy higher than 75%. If I can't achieve an accuracy higher than 75%, I will need to make at least three attempts to do so.
## Results
### Data Preprocessing
* What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL
* What variable(s) are considered to be the features for your model? The remaining variables in the DF
* What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* Were you able to achieve the target model performance?
* What steps did you take to try and increase model performance?

## Summary
None of the optimization attempts in this analysis were able to produce a model with a predictive accuracy level of 75% or higher. With the variations of increasing the epochs, removing variables, adding an additional hidden layer, and/or increasing/decreasing the neurons, the changes were minimal.
