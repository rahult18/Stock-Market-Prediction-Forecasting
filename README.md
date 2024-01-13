# Stock Market Prediction & Forecasting

## Abstract

Expectations on financial exchange costs and stock market prices are of great ultimatum due to their constantly changing nature and complexity. In this project, we aim to predict stock market prices using Machine Learning (ML) techniques, specifically utilizing a recurrent neural network (RNN) model, especially the Long Short-Term Memory (LSTM) approach, and the Ensemble Technique with the Random Forest Model to predict stock trends.

## Problem Statement

We analyze the best approach for predicting stock market trends, considering feature engineering, financial domain data, and algorithms. Three research questions are addressed: the role of feature engineering in model accuracy, the potency of insights from the financial domain, and determining the best algorithm for predicting stock markets.

## Proposed Architecture

Our model incorporates a Long Short-Term Memory (LSTM) network, designed for more accurate long-term predictions in stock market data. The generic workflow includes stages such as collecting raw data, data pre-processing, feature extraction, training the model, output generation, fine-tuning parameters, and visualization.
\
\
LSTM model's architecture \
<img alt="image" src="https://github.com/rahult18/Stock-Market-Prediction-and-Forecasting/assets/59415849/50ed2174-063a-4349-a448-7dbf9fde04eb">


### Stages

1. **Collecting Raw Data:** Gather historical data from reliable sources like Yahoo Finance, NSE, and BSE.

2. **Data Pre-processing:**
   - Data discretization for numerical data.
   - Normalizing data.
   - Filling missing values.
   - Partitioning data into training (75%) and testing (25%).
   - Incorporating Technical Indicators (Only for Random Forest).

3. **Feature Extraction:** Choose relevant features to feed into the model using feature extraction techniques.

4. **Training the Model:**
   - LSTM Model: Sequential input layer, LSTM layers, and a dense output layer with a linear activation function.
   - Random Forest Model: Computed technical indicators, converted dataset into binary classification data (up days and down days).

5. **Output Generation:** Compare output with target value, minimize errors using backpropagation algorithm.

6. **Fine-tuning the Parameters:** Repeat data pre-processing and feature extraction for the test dataset.

7. **Visualization:** Visualize forecasted results from LSTM RNN network and predictions from the Random Forest Model.
   
\
\
Graphical Representation of Workflow
\
<img alt="image" src="https://github.com/rahult18/Stock-Market-Prediction-and-Forecasting/assets/59415849/d6560172-d764-407c-9abc-bdc65f067572">


## How to Use

Download the weighted model and the notebook and run the notebook on Jupyter Notebook / Google Colab. Happy Forecasting!
