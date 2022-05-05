# HFT-using-Machine-Learning
My first high-frequency trading model using machine learning

I used 1 month length of 1 second high-frequency ES futures data with 30 levels of order book to train and test the model. PCA and supervised autoencoder are used to compress the features, and lightgbm with hyperparameters tuning using optuna is used to produce the final model. 

Backtrader is used to backtest the hft model with transaction cost in the end. 
