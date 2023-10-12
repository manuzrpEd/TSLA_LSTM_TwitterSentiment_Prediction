# TSLA_LSTM_TwitterSentiment_Prediction

This project predicts TSLA stock prices using Twitter Sentiment on TSLA as a feature. This repository draws inspiration from [https://github.com/georgemuriithi/tesla-stock-price-pred/tree/main](https://github.com/georgemuriithi/tesla-stock-price-pred/tree/main) and is intended for educational purposes. Additionally, it serves as a showcase of my coding and machine learning proficiency.

The repository demonstrates a fine-tuning process for an LSTM (Long Short-Term Memory) neural network using the Ray API. LSTM networks are powerful models for sequential data, and fine-tuning allows us to adapt pre-trained models to specific tasks or datasets.

Areas for improvement:

* Predict next step prices, not contemporaneous prices as it is now.
* Address scaler lookahead bias: scaler on training data, not on full data as it is now.
* Predict returns, not prices
