# HFT-using-Machine-Learning
My first high-frequency trading model using machine learning (LightGBM and CNN + Transformer)

I used 1 month length of 1 second high-frequency ES futures data with 15 levels of order book each side to train and test the model. PCA and supervised autoencoder are used to compress features, and Lightgbm with hyperparameters tuning using optuna and Transformer are used in training. 

Backtrader is used in the end to backtest the HFT model.

HFT_Project 1 and 2 used LightGBM with different settings of features

HFT_Project_deeplearning_transformer used CNN to extract order book features from 15 levels of orderbook data and a transformer.

Simple backtest without considering queue position 
<img width="1002" alt="Screenshot 2022-06-11 at 06 28 44" src="https://user-images.githubusercontent.com/49976973/173174218-90a8149e-8b77-4b34-bcd8-e806268dcf0e.png">
<img width="223" alt="Screenshot 2022-06-11 at 06 28 53" src="https://user-images.githubusercontent.com/49976973/173174223-9844df0b-3761-4754-9ae8-3ea7c7d7ea0e.png">
