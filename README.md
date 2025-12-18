# Valence Predictor - A Deep Learning Group Project

In this group project (at Tilburg University) we had to create a Deep Learning model to predict valence in audio signals by using PyTorch.

We were given a raw speech dataset (pickle files) on which we first had to perform some preprocessing and feature engineering. We were given the freedom to try out any model of our choice. 


After experimenting with several different models (see Report) we decided to use a bidirectional LSTM (See Python notebook) - this model gave us the best score without significant overfitting problems.


## Why LSTM?

LSTMs are highly adaptable, which makes them robust for messy, real-world time series data where patterns can be irregular or interrupted. LSTMs outperform simpler models in scenarios involving complex, non-linear relationships or variable-length dependencies (like in our case). 
