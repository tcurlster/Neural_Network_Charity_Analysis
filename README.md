# Neural_Network_Charity_Analysis
## Overview
The purpose of this project was to develop a deep learning neural network to classify the success of charitable donations.

In this project, I started with a dataset that compiled all charitable donations, cleaned it up with preprocessing, developed the neural network and trained the model; and finally attempted to optimize the model to reach a 75% accuracy score.

## Results
### Data Preprocessing
- The IS_SUCCESSFUL variable is considered the target for our model to determine if a donation was used appropriately.
- The feature variables that we used to predict the successfulness were as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION,USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONSIDERATIONS
- The EIN and NAME variables were removed from the dataset since they did not impact the outcome of the model prediction

### Compiling, Training, & Evaluating the Model
- I used 2 hidden layers with 80 neurons in the first hidden layer and 30 neurons in the second hidden layer for the first run of our model. With so many variables included in our data, I wanted to ensure that there were enough layers and neurons to capture enough test cases. 
- I was unable to get my model to perform above 73% accuracy
- After not reaching the 75% target, I then added a third layer and changed the neuron to 80, 50, and 30 respectively. I also changed the bucketing of the "Other" APPLICATION TYPES from 500 to 800 and also adjusted the activation functions to see if they had any impact on the accuracy. Unfortunately, they did not

## Summary
Since this model did not reach a 75% accuracy score, I believe there are other methods that would be more successful.  Using a supervised learning classification type of model such as decision trees or random forest may fit this dataset better to predict better results.


