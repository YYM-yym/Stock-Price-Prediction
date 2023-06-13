# Stock-Price-Prediction
## Description
This project focuses on sentiment analysis of Twitter stock comments and uses various natural language processing (NLP) techniques to predict stock prices based on the predicted sentiment, historical stock data, and deep learning models such as GAN (Generative Adversarial Network) and LSTM (Long Short-Term Memory).

## Features
- Collects real-time Twitter stock comments related to specific stocks.
- Performs sentiment analysis on the collected comments using three different NLP models:
   - Textblob: A library for processing textual data, providing a simple API for sentiment analysis.
   - Flair: A state-of-the-art NLP library that offers a wide range of pre-trained models for sentiment analysis and other tasks.
   - SentimentIntensityAnalyzer: A rule-based sentiment analysis tool provided by the Natural Language Toolkit (NLTK) library.
- Generates sentiment scores and labels (positive, negative, neutral) for each comment.
- Combines the sentiment scores with historical stock price data.
- Trains a GAN model to generate synthetic stock price sequences based on the sentiment and historical data.
- Utilizes LSTM networks for stock price prediction, considering the generated synthetic data as well.
- Evaluates the performance of the prediction models using various metrics.

## File list 
- **sentiment analysis-Lemm _ Textblob.ipynb** Data preprocessing and sentiment analysis powered by Textblob.
- **sentiment analysis-Flair.ipynb** Sentiment analysis powered by Flair.
- **sentiment analysis-sentiment analyzer.ipynb** Sentiment analysis powered by SentimentIntensityAnalyzer.
- **EDA.ipynb** Explanatory Data Analysis.
- **time-series prediction.ipynb** Time series prediction using LSTM and GAN.
