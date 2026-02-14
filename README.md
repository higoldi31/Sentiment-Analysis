# Sentiment Analysis with Simple RNN

This project implements a sentiment analysis model using a Simple Recurrent Neural Network (RNN) with TensorFlow/Keras. The model is trained on the IMDB movie reviews dataset to classify reviews as positive or negative.

## 📋 Overview

The notebook covers the complete pipeline for sentiment analysis:
- Text tokenization and sequence generation
- Padding sequences for uniform input length
- Building a SimpleRNN model with embedding layer
- Training on IMDB dataset
- Making predictions on custom text inputs

## 🧠 Model Architecture

- **Embedding Layer**: Converts words to dense vectors (2-dimensional embeddings)
- **SimpleRNN Layer**: 32 units with return_sequences=False
- **Dense Output Layer**: Single neuron with sigmoid activation for binary classification

## 🛠️ Technologies Used

- Python 3
- TensorFlow/Keras
- IMDB Dataset (built into Keras)
- NumPy

## 📊 Dataset

The IMDB dataset contains 50,000 movie reviews labeled as positive or negative:
- 25,000 training samples
- 25,000 test samples
- Limited to top 10,000 most frequent words
- Reviews padded/truncated to 50 words

