# Evaluation of time-series forecasting using ARIMA and LSTM-RNN
Forecasting a time dependent data involves predicting future values based on the past data. This is done by analyzing historical data using various statistical and machine learning techniques. Time-series forecasting is used to derive useful information in various domains involving a time-dependent variable that has data accumulated over a period of time like stock prices, weather and sales data. Valuable insights can be obtained by understanding the underlying patterns and trends. This project employs a non-linear algorithm, LSTM-RNN (Long Short-Term Memory Recurrent Neural Network), and a linear algorithm, ARIMA (AutoRegressive Integrated Moving Average), to forecast the movement of the stock index or the daily closing price of the stock.

This project aims to evaluate the performance of two popular time-series forecasting models, ARIMA and LSTM-RNN, and select the best model for a given dataset.

## Getting Started

To get started with this project, you will need to have Python 3.x installed on your machine. Additionally, you will need to install the following packages:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Keras

These packages can be installed using pip, a package installer for Python.

```
pip install pandas numpy matplotlib scikit-learn keras

```

## Dataset

The dataset used in this project is [insert dataset name and source], which contains [insert details about dataset].

## Usage

To run the code, simply navigate to the project directory in your terminal and rename the .ipynb file as main.py and run the following command:

```
python main.py

```

This will train both the ARIMA and LSTM-RNN models on the dataset and output the evaluation metrics for each model.

## Results

After evaluating the performance of both models on the dataset, we found that LSTM-RNN outperforms ARIMA in terms of prediction accuracy for time-series datasets. This can be attributed to the ability of LSTM-RNNs to capture complex patterns in the data and remember the information derived from long sequences of input data.