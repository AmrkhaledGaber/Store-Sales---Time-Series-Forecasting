Store Sales - Time Series Forecasting

Project Overview : 
  - Data Loading and Preprocessing:
        Load the data from various CSV files provided by Kaggle.
        Merge and clean the data, handling missing values and irrelevant columns.
        Encode categorical variables and scale numerical variables.
   - Model Training:
        Train a neural network model using Keras with dropout and L2 regularization.
        Implement custom accuracy metrics to evaluate model performance.
    -Evaluation:
        Plot training and validation loss to visualize model performance.
        Use the trained model to make predictions on the test data.
        Save the predictions to a CSV file for submission to Kaggle.
    - Time Series Forecasting with LSTM:
        Prepare the data for time series forecasting by creating sequences.
        Train an LSTM model to capture temporal dependencies in the sales data.
        Evaluate and visualize the LSTM model's performance.

Key Features :
    -Custom Accuracy Metric: A custom accuracy function is used to evaluate the model's performance, focusing on predictions within a specific threshold.
   - Data Integration: Merging multiple datasets (sales, stores, oil prices, holidays, and transactions) to enrich the training data.
   -Regularization: Implementing dropout and L2 regularization in the neural network to prevent overfitting.
    -Time Series Forecasting: Using LSTM networks to model and predict future sales based on past data.

Repository Structure
    -train.csv: Training data with historical sales records.
    -test.csv: Test data for making predictions.
    -oil.csv: Daily oil prices.
    -holidays_events.csv: Holiday and event data.
    -stores.csv: Information about the stores.
    -transactions.csv: Transaction data for each store.
    -model.py: Python script containing the neural network model.
    -lstm_model.py: Python script containing the LSTM model.
    -README.md: Project description and instructions.

Requirements
    Python 3.x,
    pandas,
    numpy,
    scikit-learn,
    tensorflow,
    keras,
    matplotlib
