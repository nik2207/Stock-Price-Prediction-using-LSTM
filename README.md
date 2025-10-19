# Stock-Price-Prediction-using-LSTM

This project demonstrates how to use a Long Short-Term Memory (LSTM) neural network for predicting stock prices based on historical time series data. The model captures sequential dependencies in stock data to forecast future prices.

🚀 Project Overview

Stock prices are highly volatile and depend on multiple factors. Traditional linear models often fail to capture these nonlinear temporal relationships.
This project applies deep learning (LSTM) to analyze historical stock price data and predict the next-day closing prices.

The notebook includes:
Data preprocessing and normalization
Sequence generation for LSTM input
Model design, training, and evaluation
Visualization of actual vs predicted stock prices

🧠 Model Architecture

Input Layer: Time-series window of past stock prices
LSTM Layers: Capture sequential dependencies
Dense Layer: Outputs predicted stock price
Loss Function: Mean Squared Error (MSE)
Optimizer: Adam

🧰 Technologies Used
Category	Tools / Libraries
Programming Language	Python
Deep Learning	TensorFlow, Keras
Data Analysis	Pandas, NumPy
Visualization	Matplotlib
Environment	Google Colab / Jupyter Notebook

Results
The model learns the trend and gives visually comparable predictions with actual stock prices.
Key Visualizations:
Training vs Validation Loss
Predicted vs Actual Price Curve
(Example plot)
