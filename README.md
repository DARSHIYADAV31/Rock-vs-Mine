Sonar Object Classification
This project involves implementing a machine learning pipeline to classify objects as either rocks or mines based on sonar signal data. The process includes data collection, preprocessing, model training, evaluation, and prediction.

Dependencies
numpy
pandas
scikit-learn
Data Collection and Processing
Load the dataset into a pandas DataFrame.
Display the first few rows, shape, and statistical measures of the dataset.
Count the instances of each class (R for Rock and M for Mine).
Group the data by class and compute the mean values.
Separate the dataset into features (X) and labels (Y).
Splitting the Data
Split the dataset into training and test sets using an 90-10 split, stratified by class.
Model Training
Train a Logistic Regression model using the training data.
Model Evaluation
Evaluate the accuracy of the model on both training and test data.
Making Predictions
Implement a predictive system to classify new input data as either Rock or Mine.# Rock-vs-Mine
