# Simple-Linear-Regression


Readme.md
Project: Simple Linear Regression on Iris Dataset with Scikit-learn

Description:

This project demonstrates the implementation of simple linear regression using the scikit-learn library in Python. It utilizes the Iris dataset to predict the petal width based on the petal length.

Steps:

Load the Iris dataset using Seaborn's load_dataset function.
Select the relevant features: "petal_length" and "petal_width".
Split the data into training and testing sets using train_test_split.
Convert the feature column ("petal_length") to a NumPy array with the desired shape for training.
Create a LinearRegression model object using Scikit-learn.
Train the model using the training data (feature and target variables).
Obtain the model's intercept (c) and coefficient (m) for the linear equation.
Predict the target variable (petal_width) for the training data using the model and compare it to the actual values.
Visualize the training data points and the predicted values using a scatter plot.
Predict the target variable for the testing data using the model.
Visualize the testing data points and the predicted values using a scatter plot.
Results:

The linear regression model is able to capture the relationship between petal length and petal width in the Iris dataset. The predicted values for both training and testing data sets follow a similar trend to the actual values, indicating that the model has learned a meaningful relationship between the features.

Conclusion:

This project provides a basic example of linear regression using Scikit-learn and demonstrates its application on a real-world dataset. It highlights the steps involved in data preparation, model training, prediction, and visualization.


