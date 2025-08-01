# IMDB-Sentiment-Analysis

This project implements sentiment analysis on IMDB movie reviews using a Bi-directional LSTM neural network.This paper presents a comparative study of three neural
network architectures for sentiment analysis: a baseline
Feed-Forward Neural Network (FFNN), a sequence-aware
Bidirectional Long Short-Term Memory (Bi-LSTM) net-
work, and an FFNN enhanced with Dropout regulariza-
tion. The models are evaluated on the IMDB movie re-
view dataset. Experimental results show that the Bi-
LSTM achieves the highest test accuracy (86.76%), nar-
rowly outperforming the regularized FFNN (86.68%) and
the original FFNN (86.54%). The findings highlight the
inherent advantage of sequence-modeling architectures
for language tasks, while also demonstrating that regu-
larization provides a marginal but clear benefit to the
simpler FFNN model.

## Project Structure

- `Bi_directional_LSTM.ipynb`: Jupyter notebook containing data preprocessing, model building, training, and evaluation.
- `FF_vs_LSTM_NN.pdf`: Comparison between Feedforward and LSTM neural networks.
- `download.png`: Image asset used in the project.

## Features

- Preprocesses IMDB review data for sentiment analysis.
- Builds and trains a Bi-directional LSTM model to classify reviews as positive or negative.
- Evaluates model performance and displays predictions.

## Getting Started

1. Clone the repository.
2. Open `Bi_directional_LSTM.ipynb` in Jupyter Notebook.
3. Run the notebook cells to preprocess data, train the model, and evaluate results.

## Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch (depending on implementation in the notebook)
- NumPy
- Pandas