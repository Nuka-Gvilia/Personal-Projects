# Tweet Emotion Recognition

## Project Intro/Objective
Build an LSTM model with TensorFlow that determines the emotion of a tweet.

This project only contains the Python Jupyter notebook with code. 

## Models Used
- LSTM
- Keras Word Embedding

## Technologies 
- Python
- Google Colab

## Dataset
Emotion dataset from Huggingface. Dataset with more information can be found [here](https://huggingface.co/datasets/emotion)

The dataset consists of train, validation and test parts. Every tweet belongs to one of these six categories:
- sadness
- joy
- love
- anger
- fear
- surprise

## Methdology

Preprocess training dataset by tokenizing, truncating and padding the tweets. Train a neural network model with an Embedding layer, two LSTM layers and a final Dense layer using the softmax activation function. Evaluate the model on the validation and test sets.
