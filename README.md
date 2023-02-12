# crypto_sentiment_bert
Experiments to determine the tone of tweets on crypto topics

As supporting data for time series prediction models (stock market/crypto exchanges), it is worth paying attention to the general news background.

For this purpose, based on several neural network approaches, including BERT, I conducted several experiments to estimate the tone of tweets. That is, the problem comes down to the classification task -- 3 classes: (Negative, Positive, Neutral).

Full code presented in 3_models.ipynb file.

Link for training dataset: https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets/versions/17?resource=download&select=Bitcoin_tweets.csv

BERT models: 
> https://huggingface.co/yiyanghkust/finbert-tone
> https://huggingface.co/ElKulako/cryptobert
