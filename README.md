# RNN-and-LSTM-model-on-a-dataset
Using RNN and LSTM model on a dataset.

Dataset link : https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv

Dataset contains the Temperatures in lebourne Australia from 1981-1990 year 

1. Time Series Forecasting using Recurrent Neural Network (RNN).
2. Time Series Forecasting using Long Short-Term Memory (LSTM).


1. Import Libraries:

Import necessary libraries like pandas, numpy, tensorflow, and matplotlib to handle the dataset, build the models, and visualize results.
2. Load the Dataset:

Load the "daily minimum temperatures" dataset containing temperature readings for Melbourne using pandas.

3. Data Preprocessing:

Extract the target variable (Temperature), normalize the data using MinMaxScaler, and split it into training (80%) and testing (20%) sets.

4.Prepare Data for RNN/LSTM:

 Create sequences of temperature data to represent time steps for the RNN and LSTM models. Reshape the data to fit the required input format.
 
5. Build the RNN Model:
Define a simple RNN model with one SimpleRNN layer and a Dense output layer to predict the next temperature.

6.Train the RNN Model:
Train the RNN model using the training data for 20 epochs and validate using the test data.

6. Build the LSTM Model:
Define an LSTM model with an LSTM layer and a Dense output layer for temperature prediction.

8.Train the LSTM Model:
Train the LSTM model using the same approach as the RNN, for comparison.

9.Make Predictions and Evaluate:
Make predictions using both models and calculate the Mean Squared Error (MSE) for performance evaluation.


10.Visualize the Results:

Plot the actual temperatures and predictions from both models to visually compare their performance.


This project demonstrates the use of RNN and LSTM for time series forecasting, comparing their ability to predict future temperature values based on historical data.






   
