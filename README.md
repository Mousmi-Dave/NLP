**Fake Dataset Classification using Bidirectional LSTM**

Overview

This project demonstrates text classification on a dataset containing fake and real entries. The goal is to predict whether a given text is fake or not using a Bidirectional LSTM model.Bidirectional LSTMs are a type of recurrent neural network (RNN) that process data in both forward and backward directions, capturing context from past and future tokens in the sequence, which improves performance on text data.

Approach

(i) Data Preprocessing:
Text cleaning (removing punctuation, special characters)
Tokenization
Padding sequences to ensure uniform input length
Encoding labels (0 for Real, 1 for Fake)

(ii)Model Architecture:
Embedding layer to convert words into dense vectors
Bidirectional LSTM layer(s) to capture contextual dependencies
Dense layers for final classification
Activation function: sigmoid for binary classification

(iii)Training:
Loss function: Binary Crossentropy
Optimizer: Adam
Metrics: Accuracy
