# TSLA_LSTM_TwitterSentiment_Prediction

This project predicts TSLA stock prices with and without Twitter Sentiment.

This repository demonstrates a fine-tuning process for an LSTM (Long Short-Term Memory) neural network using the Ray API. LSTM networks are powerful models for sequential data, and fine-tuning allows us to adapt pre-trained models to specific tasks or datasets.

Areas for improvement:

* Predict next step prices, not contemporaneous prices as it is now.
* Address scaler lookahead bias: scaler on training data, not on full data as it is now.
* Predict returns, not prices