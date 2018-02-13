# Binary_classification-Keras
The following notebook is a very easy guideline to follow for creating your own ANN(Artificial Neural Network).

2 approaches have been used. One where we have used (Wrappers for the Scikit-Learn API-Keras). Check out the link here https://keras.io/scikit-learn-api/ It is basically creating your own function for the keras model and then calling it using the wrappers. For validation the kfold data split technique is used.
The other aproach is our standard sequential initializing module method. Both give an accuracy value which is approximately the same.

DataSet-
Our basic aim is to predict customer churn for a certain bank i.e. which customer is going to leave this bank service. Dataset is small(for learning purpose) and contains 10000 rows with 14 columns.  You can download data from https://drive.google.com/file/d/0By9Y49AzZGaUemtpNWtQMWdqRDA/view.
