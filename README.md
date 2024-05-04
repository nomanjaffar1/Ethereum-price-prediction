# Ethereum-price-prediction
<br>

This repository contains Python code for an Ethereum price prediction model using a neural network built with TensorFlow. The script reads Ethereum historical data from a CSV file and preprocesses it to handle volume strings, convert string values to numerical formats, replace outliers, and extract date features for time-series analysis. The neural network model, constructed using TensorFlow's Keras API, consists of dense layers for regression to predict Ethereum price, high, and low values based on features like opening price, volume, and date components. The model is trained and evaluated using mean squared error (MSE), mean absolute error (MAE), root mean squared error (RMSE), and R-squared (R^2) score to assess performance. To use, place your Ethereum historical data CSV file (Ethereum Historical Data.csv) in the appropriate location or update the file path accordingly, then run the script to preprocess data, train the model, and make predictions. Customize input data for prediction by modifying the sample data (data) with specific values, and adapt the model for other time-series prediction tasks by adjusting input features and target variables. Ensure necessary libraries (numpy, pandas, matplotlib, seaborn, tensorflow) are installed.