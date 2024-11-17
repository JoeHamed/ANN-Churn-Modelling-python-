###Customer Churn Prediction Using ANN
This project demonstrates how to build, train, and evaluate an Artificial Neural Network (ANN) to predict customer churn using the Churn_Modelling.csv dataset.

Overview
The project uses TensorFlow to create an ANN for binary classification, predicting whether a customer will leave a bank. It includes steps for data preprocessing, model creation, training, and evaluation.

Steps
Data Preprocessing:

Encode categorical data.
Split data into training and test sets.
Apply feature scaling.
Building the ANN:

Input layer, two hidden layers (ReLU activation), and one output layer (Sigmoid activation).
Compiled using Adam optimizer and binary cross-entropy loss.
Training:

Trained on 100 epochs with a batch size of 32.
Evaluation:

Confusion matrix and accuracy score used for performance evaluation.
Results
Accuracy: 86%
Requirements
Python 3.x
TensorFlow
NumPy
Pandas
scikit-learn
