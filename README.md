# deep-learning-challenge

# Report

Overview of the analysis: The purpose of this analysis is to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing

#### What variable(s) are the target(s) for your model?
    - Target variable is the 'IS_SUCCESSFUL' data

#### What variable(s) are the features for your model?
 - Feature variables are the data from the other columns in the dataframe, such as:
    - APPLICATION_TYPE—Alphabet Soup application type
    - AFFILIATION—Affiliated sector of industry
    - CLASSIFICATION—Government organisation classification
    - USE_CASE—Use case for funding
    - ORGANIZATION—Organisation type
    - STATUS—Active status
    - INCOME_AMT—Income classification
    - SPECIAL_CONSIDERATIONS—Special considerations for application
    - ASK_AMT—Funding amount requested

#### What variable(s) should be removed from the input data because they are neither targets nor features?
    - The 'EIN' and 'NAME' columns were removed

### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
 - For the best attempt (Optimisation3), I selected 5 hidden layers with the following details: 
  - 1 hidden layer: 10 neurons
  - 2 hidden layer: 8 neurons
  - 3 hidden layer: 3 neurons
  - 4 hidden layer: 2 neurons
  - 5 hidden layer: 1 neuron
  The values were picked (randomly) trying to obtain a higher Accuracy.

#### Were you able to achieve the target model performance?
The model didn't achieve the 75% of accuracy. It achieved 73.95%.

#### What steps did you take in your attempts to increase model performance?
- The steps taken were to add more hidden layers and to vary the number of neurons.

### Summary: 
- The target model performance was not achieved. This highlights that we may need additional data to train the model or by varying activation functions and further iterations to achieve higher accuracy.