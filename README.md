# Neural_Network_Charity_Analysis

## Analysis Overview
This project is about the use of Neural Network and creating Deep Learning Models to help analyze the utilization of charitable donations to the recipients by Alphabet Soup, a nonprofit foundation, that aims to protect environment. We used 3 methodologies to evaluate to name: 
* •	Data preprocessing for the neural network model,
* •	Design, train evaluate and export neural networks 
* •	optimize the model.
## Resources
•	Data Source: charity_data.csv containing 34,000 organizations as recipients of funding by Alphabet Soup 
* •	Applications: TensorFlow platform in Python, Mlenv Jupiter Notebook 
## Results
### Data Preprocessing
* •	We removed/hide sensitive information columns *EIN* and *NAME* 
* •	The column *IS_SUCCESSFUL* which contains binary data was used as the basis on whether or not the charity donation was used effectively. 

* •	 We used the columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT as the features for our model. Encoding of the categorical variables, splitting into training and testing datasets and standardization have been applied to the features.
### Design, Training and Evaluating the Model
* •	The deep-learning neural network model made up of two hidden layers with 80 and 30 neurons respectively. Each layer has a series of activation function.
The output layer is made of a unique neuron as it is a binary classification.
We applied the activation function Relu to speed up the training process and *sigmoid* as the output layer
* •	The target is to achieve 75% accuracy or higher which involves adjusting of input data by dropping, adding columns.
* •	We tried to improve the performance of the model thru *bucketing* 
## Summary:

Though we reached an outcome of 72.6%, it was below the goal of reaching the model accuracy of 75%. We should try to increase the data or get the right feature combination and run more attempts tests. Also, we can use other supervised machine learning model such as Random Forest Classifier with a combination of decision trees and further evaluate against the output of our deep learning model 

