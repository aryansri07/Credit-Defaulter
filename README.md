# Credit-Defaulter

## Introduction
Binary Classifier with a unique combination of datasets to predict if it was safe for a bank to loan them money or not. 

## Workflow
- We had to use both the user demographic data which was provided with anonymous labels along with the user payment history data.
- Since the dataset was heavily skewed we performed the binary classification using oversampling and undersampling with tomek links to balance out the data and make it easier for the model to train with better accuracy, it also consisted of some EDA using Pandas, performed some feature engineering and manipulating the data to get better results.
- We also used and tested a wide array of models and tuned hyperparameters.
 ## Result
After multiple tries, We found the Gradient Boost algorithm to give the best results out of the various models we tried.
