# Stock_Prediction_Using_RNNs

This project was part of my final assignment in COMP 432: Machine Learning at Concordia University.

The goal of this project was to see if it possible to train RNNs to predict stock market results.
This was to be done using and comparing GRU and LSTM recurrent neural networks. The
experiments were done on Apple’s stock and using the VIX and Nasdasq indices to perform the
prediction.

## How to Run

The main notebook to run the experiment is called Stock_Prediction_using_RNNs.ipynb.

## Results

The results of the experiments are stored in two files called gru_final_results and lstm_final_results.
A report is also provided explaining the design choices of the project and how they were implemented

## Hyperparameter Search

To run a Hyperparameter search, simply uncomment the commented cell with the comment "#Hyperparameter training."
in the RNN training part of the notebok and the cells in Hyperparameter Plotting part.

## Requirements

python >= 3.7\
pip >= 21.3.1\
yfinance >= 0.1.70\
numpy >= 1.20.3\
torch >= 1.9.1\
sklearn >= 1.0.1\
matplotlib >= 3.5.1\
