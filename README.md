# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of the analysis is to use machine learning and neural networks features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 
- Data Preprocessing
    1. What variable(s) are considered the target(s) for your model?
    The target(s) for th9s model is the IS_SUCCESSFUL column.
    2. What variable(s) are considered to be the features for your model?
    The variables which are considered to be the features are all variable expect for those we dropped. 

    3. What variable(s) are neither targets nor features, and should be removed from the input data?
    The variables we dropped are 'EIN' & 'NAME' as these tho variables are neither targets nor features that will impact the result.

- Compiling, Training, and Evaluating the Model
    1. In the deep-learning neural ntework model, there are 2 hidden layers with 80 and 30 neurons. The input shape was (42) and output layer's neurons was 1 (binary_classification). The  sigmoid function is used as activation functionThe. Loss metrics setting is binary_crossentropy.
    2. The model predictive accuracy is less than 75% which means the model designed is not able to accurately predict the result.

    3. The steps I took to try and increase model performace: I added more hidden layers of total 3 and 4 in the AlphabetSoupCharity_Optimzation. I dropped "SPECIAL_CONSIDERATIONS_Y",  "SPECIAL_CONSIDERATIONS_N" columns as majority is without speccial consideration. I also tried using relu and tanh activation but it didn't increase the accuracy rate.


## Summary: 
The model accuracy rate is around 72.6% which is slightly below the 75% mark. The recommendation for improving the prediction is that we might need to get more understanding for the meaning behind the data and understaning the criteria for the decision. Then we can drop more irrelevant columns to peform more accuracy preditcion.