# IMDb Sentiment Analysis using LSTM and GloVe Embeddings

This project demonstrates sentiment analysis on the IMDb movie review dataset using a Long Short-Term Memory (LSTM) network and GloVe embeddings. The goal is to classify movie reviews as positive or negative based on their textual content.


## Overview
Sentiment analysis is a common Natural Language Processing (NLP) task where the objective is to determine the sentiment expressed in a piece of text. This project uses an LSTM network, which is well-suited for sequence data, and pre-trained GloVe embeddings to capture semantic meaning.

## Dataset
The IMDb dataset is a well-known dataset for binary sentiment classification. It contains 50,000 movie reviews labeled as either positive or negative. The dataset is split evenly with 25,000 reviews for training and 25,000 for testing.

Download IMDB Dataset : https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Download Glove Emebedding :  http://nlp.stanford.edu/data/glove.6B.zip

Extact  glove.6B.zip and move glove.6B.100d.txt to working directory

## Model Architecture
The model architecture consists of the following layers:
- **Embedding Layer**: Initialized with pre-trained GloVe embeddings.
- **LSTM Layer**: Captures long-term dependencies in the text.
- **Dense Layer**: Fully connected layer to interpret LSTM output.
- **Output Layer**: Sigmoid activation to output probability of positive sentiment.

