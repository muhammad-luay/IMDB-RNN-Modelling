# IMDB Sentiment Analysis with TensorFlow
Deep Learning models for sentiment analysis on the IMDB movie reviews dataset using TensorFlow and Keras.

## Overview
This repository contains code and models that target sentiment analysis tasks on the IMDB movie reviews dataset. We explore various neural network architectures, from Simple RNNs to advanced Bidirectional LSTMs, to classify movie reviews as positive or negative.

## Table of Contents
1. Features
2. Prerequisites
3. Setup
4. Usage
5. Contributions

### Features
Data Preprocessing: Tokenization and padding of the reviews.
Neural Network Models:
1. Simple RNN
2. Regularized RNN with Dropout
3. Bidirectional LSTM
4. Conv1D with Bidirectional LSTM
5. Callbacks: Implementation of early stopping and model checkpoints.

### Prerequisites

Python 3.x <br>
TensorFlow 2.x <br>
Keras <br>
TensorFlow Datasets <br>

### Setup
Clone the repository:

```git clone https://github.com/muhammad-luay/IMDB-RNN-Modelling```

```cd IMDB-RNN-Modelling```


(Optional) It's recommended to set up a virtual environment:

```python3 -m venv venv```

```source venv/bin/activate```

Install the necessary packages:

```pip install jupyter tensorflow tensorflow_datasets numpy```

### Usage

Launch Jupyter Notebook:

```jupyter notebook```

Navigate to the notebook file (rnn.ipynb) and open it.

Execute cells step by step to follow the analysis or run the entire notebook.

Once trained, models can be utilized to predict sentiments of new movie reviews. 

## Contributions

Contributions to enhance the notebook or to provide additional insights are highly appreciated. Whether it's through issue discussions or pull requests, your input is valuable!
