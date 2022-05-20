# HFT-using-Machine-Learning
My first high-frequency trading model using machine learning (LightGBM and CNN + Transformer)

I used 1 month length of 1 second high-frequency ES futures data with 15 levels of order book each side to train and test the model. PCA and supervised autoencoder are used to compress features, and Lightgbm with hyperparameters tuning using optuna and Transformer are used in training. 

Backtrader is used in the end to backtest the HFT model.
HFT_Project 1 and 2 used LightGBM with different settings of features
HFT_Project_deeplearning_transformer used CNN to extract order book features from 15 levels of orderbook data and transformer to build HFT model.
