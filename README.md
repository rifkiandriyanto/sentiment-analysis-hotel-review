# Hotel Review Sentiment Analysis

This repository contains code and resources for performing sentiment analysis on hotel reviews using a variety of deep learning models and techniques. The models integrate advanced NLP tools and embeddings such as FastText, Word2Vec, Doc2Vec, along with neural network architectures like BERT, LSTM, BiLSTM, andd BiLSTM-attention.

## Models Overview

The repository explores the following model architectures:

- **BERT-Based Models**:
  - **BERT-FastText**: Integrates BERT embeddings with FastText for robust feature extraction.
  - **BERT-Word2Vec**: Combines BERT embeddings with Word2Vec.
  - **BERT-Doc2Vec**: Utilizes BERT along with Doc2Vec embeddings.

- **LSTM Models**:
  - **LSTM-FastText**: Standard LSTM model with FastText embeddings.
  - **LSTM-Word2Vec**: LSTM with Word2Vec embeddings.
  - **LSTM-Doc2Vec**: LSTM integrated with Doc2Vec embeddings.

- **BiLSTM Models**:
  - **BiLSTM-FastText**: Bi-directional LSTM with FastText.
  - **BiLSTM-Word2Vec**: Bi-directional LSTM using Word2Vec.
  - **BiLSTM-Doc2Vec**: Bi-directional LSTM combined with Doc2Vec.

- **BiLSTM with Attention Models**:
  - **BiLSTM-Attention-FastText**: BiLSTM with an attention layer using FastText.
  - **BiLSTM-Attention-Word2Vec**: BiLSTM with attention and Word2Vec embeddings.
  - **BiLSTM-Attention-Doc2Vec**: Incorporates attention mechanism with BiLSTM and Doc2Vec.

## Dataset

The dataset used for training and evaluating the models is the [515k Hotel Reviews Data in Europe](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe) from Kaggle. It consists of over half a million reviews, providing a rich set of data points for sentiment analysis.

## Setup and Installation

To run the code in this repository, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rifkiandriyanto/sentiment-analysis-hotel-review
   cd hotel-review-sentiment-analysis
