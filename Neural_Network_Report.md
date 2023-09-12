# Module 21 - Deep Learning Challenge Report

## Overview:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Data Preprocessing:

What variable(s) are the target(s) for your model?

- The 'IS_SUCCESSFUL' column from application_df

What variable(s) are the features for your model?

- The "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" columns are the features

What variable(s) should be removed from the input data because they are neither targets nor features?

- The "EIN & "NAME" columns should be removed.

# Compiling, Training, and Evaluating the Model:

## How many neurons, layers, and activation functions did you select for your neural network model, and why?

2 iterations were completed:

- 1st attempt: 2 hidden layers plus an outer layer, 
    layer 1: 20 neurons - relu activation
    layer 2: 10 neurons - relu activation
    Outer layer: 1 unit - sigmoid activation & adam optimizers as the complier.
    25 epoch

- 2nd attempt(Optomized): 3 hidden layers plus an outer layer, 
    layer 1: 20 neurons - relu activation
    layer 2: 10 neurons - relu activation
    layer 3: 5 neurons - relu activation
    Outer layer: 1 unit - sigmoid activation & adam optimizers as the complier.
    60 epochs

Were you able to achieve the target model performance?

- No, the highest score achieved was 73% (72.86297082901001)

What steps did you take in your attempts to increase model performance?

- Added a hidden layer and increase neuron nodes.
- Increased and decreased number of epochs.

Summary:

In Summary, additional attempts by adjusting variables did not increase the performance.  Next steps, I would request more data in the hopes to improve the result.
