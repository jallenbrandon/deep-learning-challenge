# deep-learning-challenge

Report on Deep Learning Model Performance for Alphabet Soup

Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a deep learning model created for Alphabet Soup. The model aims to predict whether funding applicants will be successful based on various input features.

Results

Data Preprocessing

Target Variable(s): The target variable for the model is the 'IS_SUCCESSFUL' column from the application_df.
Feature Variable(s): The feature variables include every other column from application_df, excluding the 'IS_SUCCESSFUL' column.
Variables Removed: The 'EIN' and 'NAME' columns were removed from the input data as they were neither targets nor features for the dataset.
Compiling, Training, and Evaluating the Model

Neurons, Layers, and Activation Functions: Initially, 8 neurons were used for the first hidden layer and 5 neurons for the second hidden layer, chosen somewhat arbitrarily for the first attempt. Subsequent iterations involved tweaking these parameters.
Target Model Performance: The target model performance of 75% accuracy was achieved.
Steps Taken to Improve Performance: To enhance model performance, various steps were taken, including adding more layers, removing unnecessary columns, adjusting the number of hidden nodes, and experimenting with different activation functions.
Summary

Overall, the deep learning model achieved approximately 76% accuracy in predicting the classification problem. To improve accuracy further, it's recommended to focus on data preprocessing steps to enhance the correlation between input and output variables. Additionally, experimenting with different activation functions and architectures, along with rigorous iteration, could lead to higher prediction accuracy.
