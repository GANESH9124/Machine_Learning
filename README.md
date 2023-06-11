# Machine_Learning

Linear Regression using Gradient Descent

This repository contains Python code for implementing linear regression using gradient descent. The code calculates the slope and intercept of the regression line, as well as the root mean squared error and the accuracy of the model.

Dependencies

The following libraries are required to run the code:

pandas

numpy

matplotlib

You can install them using pip:


run this command on command prompt

pip install pandas numpy matplotlib


Usage

Ensure that you have the necessary dependencies installed.

Download the Salary_Data.csv file and place it in the same directory as the Python script.
Run the Python script to execute the linear regression using gradient descent algorithm.
The script will print the slope and intercept of the regression line, the root mean squared error (RMSE), and the accuracy of the model (R2 score).
Additionally, a scatter plot of the data points and the regression line will be displayed.
Code Explanation

The code consists of the following main parts:


Importing the required libraries: pandas, numpy, and matplotlib.

Defining the mean squared error function (mean_squared_error).


Defining the partial derivatives with respect to weight and bias (dev_wrt_weight and dev_wrt_bias).
Defining the gradient descent function (grad_descent).
Defining the function to compute the R2 score (r2_score).
Initializing the parameters: weight, bias, learning rate, and maximum iterations.
Reading the data from the Salary_Data.csv file into pandas DataFrame.
Converting the DataFrame columns to NumPy arrays for training the model.
Executing the gradient descent algorithm to obtain the optimal values of weight and bias.
Computing the predicted values using the obtained weight and bias.
Computing the root mean squared error and the accuracy of the model.
Plotting the data points and the regression line.
License
This project is licensed under the MIT License.


Feel free to use the code and modify it according to your needs.
