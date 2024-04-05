
## Overview of the analysis: 
The purpose of this analysis is to create a predictive model using neural networks that can acheive an accuracy score of 75% or higher when predicting classification problems. 

Results: Using bulleted lists and images to support your answers, address the following questions:

## Data Preprocessing:
What variable(s) are the target(s) for your model?
    *The target variable was the "IS_SUCCESSFUL" cloumn of the initial application_df
What variable(s) are the features for your model?
    *The features in this model were the columns other than "IS_SUCCESSFUL"
What variable(s) should be removed from the input data because they are neither targets nor features?
    *The variables that were removed were "EIN," and "NAME" since they were neither targets or features

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
    *Initially two hidden layers were added using the relu activation. These were chosen at random as a starting point for the model. 
Were you able to achieve the target model performance?
    *The target of 75% was not reached, however there were incremental successes made on subsequent model tests
What steps did you take in your attempts to increase model performance?
    *The number of inputs were changed, and layers were added

## Summary: 
Overall, this deep learning model achieved a peak accuracy rating of 72.85%. While this score is not far off from the target goal, it is worth noting that the model that achieved this score also had a significantly higher loss rating, 79.65%, than the initial model's loss of 58.87%. 

This model could be improved with greater data cleaning in the preprocessing phase, potentially by dropping additional columns. Changing activation functions, along with further iterations of the model may also yield higher accuracy ratings. 