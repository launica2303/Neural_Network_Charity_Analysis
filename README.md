# Neural_Network_Charity_Analysis #

## Purpose: ##

We made a binary classifier using machine learning and neural networks. This was used to predict whether applicants will be successful if they are funded by Alphabet Soup. A CSV of more than 34,000 organizations that received funding from Alphabet Soup over the years was used in the analysis. The dataset was preprocessed using Pandas and Scikit-Learn’s StandardScaler(), to compile, train, and evaluate the neural network.Using knowledge of TensorFlow a prediction of 73% can be made that a organization funded by Alphabet Soup will be successful based on the features in the dataset.

## Results: ##


### •	Data Preprocessing ###

o	What variable(s) are considered the target(s) for your model?
The “Is Successful” column is the target since we want to know if they were successful or not.

o	What variable(s) are considered to be the features for your model? 

The columns kept in the second try as well as the third were: Application on type, Affiliation, Classification, Use case, Organization, Status, Income amount, Special consideration, Ask amount. The Status column was dropped in the third attempt.

o	What variable(s) are neither targets nor features, and should be removed from the input data?

For the second and third try EIN, Name, and on the third Status was taken out since these columns had no real bearing on the outcome of the results.

### •	Compiling, Training, and Evaluating the Model ###

o	How many neurons, layers, and activation functions did you select for your neural network model?

Up to 3 hidden layers were added on one try and raising the neurons.

o	Were you able to achieve the target model performance? 

75% accuracy was not achieved the highest was 73%.

o	What steps did you take to try and increase model performance? Removed columns and increased neurons 

I changed my features, activation functions, Hidden Layers, and the number of neurons in order to achieve this, as well as dropping columns.
## Summary: ##
Overall the neural network model did well with at least a 73% accuracy rate. I would recommend using the Random Forest classifier. The output and feature selection of this model are easy to understand. The data in this analysis is not to complex to need a deep learning model. 
