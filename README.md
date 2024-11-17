<h1>Short-Term Load Forecasting</h1>

This repository contains the program developed during my M.Tech in Integrated Power Systems, aimed at predicting the short-term electrical load for power systems. The project compares different machine learning models to forecast future power demand, including traditional regression models and advanced deep learning architectures.

The models explored include:

•	Regression Models

•	ARIMA

•	Attention

•	CNN-LSTM

•	GoogLeNet

•	LeNet

•	SARIMA

•	Transformer


<h2>Table of Contents</h2>

•	Introduction

•	Dataset

•	Models

•	Evaluation

•	Results

•	License

## Introduction

Short-term load forecasting (STLF) predicts the electrical load or power demand for upcoming hours, days, or weeks. This is crucial for ensuring reliable grid operations and efficient energy management. In this project, various models were applied to forecast electrical load, including classical regression models and modern deep learning approaches. The goal was to assess the models' performance across different datasets and select the best-performing ones.


## Dataset

The project utilizes two main datasets for training and evaluation:

1.	Panama Power System Load Data

    This dataset contains hourly electrical load data for the Panama power system.

3.	GEFCom2014 E Dataset

    A more extensive dataset used for global energy forecasting, which includes electrical load and weather features.

Both datasets were preprocessed to handle missing values and outliers before being used in model training.

## Models

The following models were implemented and compared:

•	Regression Models: Linear Regression, Decision Trees

•	ARIMA: AutoRegressive Integrated Moving Average

•	Attention Mechanism: Used for sequence-to-sequence learning

•	CNN-LSTM: Convolutional Neural Network combined with Long Short-Term Memory for capturing sequential dependencies

•	GoogLeNet: A deep convolutional network for feature extraction

•	LeNet: A lightweight convolutional neural network

•	SARIMA: Seasonal ARIMA for time-series forecasting

•	Transformer: Attention-based model for sequence prediction

## Evaluation

Model performance was evaluated using the following metrics:

•	Mean Absolute Error (MAE)

•	Mean Absolute Percentage Error (MAPE)

•	Root Mean Squared Error (RMSE)

## Results

Among all the models, overall GoogLeNet emerged as the best performer for both datasets, yielding the lowest error rates.

Panama Power System Dataset:

•	MAE = 0.02 (%)

•	MAPE = 1.49 (%)

•	RMSE = 0.02 (%)

GEFCom2014 Dataset:

•	MAE = 0.00 (%)

•	MAPE = 0.68 (%)

•	RMSE = 0.00 (%)

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.


