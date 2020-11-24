# Neural_Network_Charity_Analysis
Bek is Data Analytics professional, wants to develope machine learning algorith using Neural Network with the help of Tensorflow which could help the foundation predict where to make investments.

# Project Overview
The main objective of this project is to help Bek to develop the machine learning model- Neural Network (Binary classification model) that is capable of predicting whether applicants will be successful or not if funded by Alphabet Soup.

# Results

From our analysis we came to conclusion that The machine learning algorith using Neural Network was able to predict with 73.00% accuracy which is moderate in consideration. The model with higher than 75% accuracy could taken to be consideration.

## Data Preprocessing
The given dataset has multiple rows and columns. There are several columns could be voided to get better accuracy. eg. Name and EIN etc.  We can void the other feature varaibles which are causing the noise of the data and these are causing the lower the accuracy %.

But, when we are deleting the columns or feature variable we should be extra careful because out predictive outcomes depend up on the input datasets.

## Compiling, Training, and Evaluating the Model
Compilation helps us to define loss and accuracy metrics. During the training of our model, we have considered Cross-Entropy as loss function and Adam as optimizer which is normal as basic neural network.

We have taken 44 number_input_features, 80 hidden_nodes_layer1 and 30 hidden_nodes_layer2 for this projects. And we have taken reLu activation for fist hidden, second hidden layer and sigmoid for the output layer.

We created a callback that saves the model's weights every 5 epochs for our project.

# Summary
The Neural Network model seems to be moderate because of its accuracy. We can try other supervised models to evaluate and analyse the performance.

# Recommendation
We can use Random Forest as it is very simple and easy to measure the performance of the model for the same dataset since Neural Network is quite difficult to tune with number of hidden layer and it is very time consuming process to evaluate and analyse the performance.
