# Store Sales - Time Series Forecasting

This repository contains the code and resources for the "Store Sales - Time Series Forecasting" project. The goal of this project is to predict grocery sales using neural networks and time series data from Corporación Favorita, a large Ecuadorian-based grocery retailer. The forecasting model aims to improve inventory management and enhance customer satisfaction by accurately predicting future sales.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Description](#model-description)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

In this project, we aim to forecast store sales using historical sales data and other related datasets. By leveraging neural networks and LSTM models, we can capture patterns and trends in the data to make accurate predictions. The project includes data preprocessing, model training, and evaluation steps.

## Dataset

The project uses multiple datasets from the Kaggle competition Store Sales - Time Series Forecasting:
- `train.csv`: Historical sales data
- `test.csv`: Test data for making predictions
- `oil.csv`: Daily oil prices
- `holidays_events.csv`: Holiday and event information
- `stores.csv`: Store metadata
- `transactions.csv`: Store transaction counts

These datasets are merged and preprocessed to create a comprehensive dataset for training and testing the models.

## Installation

To run the code in this repository, you need to have Python 3.x installed. The following Python packages are required:

- numpy
- pandas
- scikit-learn
- tensorflow
- keras
- matplotlib




## Model Description

### Neural Network Model

The neural network model is a sequential model with dense layers and dropout regularization. It is trained to predict sales based on various features.

### LSTM Model

The LSTM model is designed for time series forecasting. It captures temporal dependencies in the data by using sequences of past sales data to predict future sales.

## Evaluation

The models are evaluated using mean squared error (MSE) and custom accuracy metrics. Training and validation loss are plotted to visualize the model's performance.

## Results

The results of the predictions are saved in a CSV file. The actual vs. predicted sales values are plotted to show the performance of the models.

## Contributing

Contributions to this project are welcome. If you have any ideas, suggestions, or bug fixes, feel free to create a pull request.

