# Next Word Prediction with LSTM

This repository implements a machine learning model for predicting the next word in a given sequence of text using LSTM (Long Short-Term Memory) networks. The model is trained on a large text dataset and uses tokenization and sequence generation to predict the next word based on a given input seed text.

## Features

- **Text Preprocessing**: The text is cleaned and tokenized to generate sequences for training.
- **LSTM Model**: A deep learning model using LSTM layers to learn patterns in the text.
- **Memory Efficient**: Uses garbage collection and session clearing to manage memory during training, especially useful for Google Colab.
- **Next Word Prediction**: Predicts the next word in a given seed text.
- **Model Checkpointing**: Saves the best model based on training loss.
  
## Installation

To use this repository, you need to have Python installed along with the following libraries:

- TensorFlow
- NumPy
- wget

You can install the dependencies using `pip`:


```bash
git clone https://github.com/your-username/next-word-prediction.git

pip install tensorflow numpy

python next_word_prediction.py




