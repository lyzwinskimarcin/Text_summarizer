# Neural Abstractive Summarization for News Articles

This repository contains the implementation of a sequence-to-sequence neural network model for the task of generating summaries from news articles. The model is designed to create concise and relevant summaries (highlights) from full-length news stories.

## Project Overview

The project utilizes an LSTM-based encoder-decoder architecture to process the input news stories and produce the corresponding summaries. The model is trained on a dataset that includes news articles paired with their summaries.

## Dataset

The dataset comprises news stories and their highlights. Each record contains a detailed article and a short summary that encapsulates the key points of the article.
Available here:
https://cs.nyu.edu/~kcho/DMQA/

## Model Architecture

The sequence-to-sequence model is composed of:
- An encoder that processes the input sequences (news stories).
- A decoder that generates the output sequences (summaries).
- An attention mechanism, allowing the decoder to focus on specific parts of the input sequence while generating each word of the summary.

## Prerequisites

To run the project, you need to have the following installed:
- Python 3.8 or higher
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib (for visualizations)
- tqdm (for progress bars)

Install the necessary libraries with the command:
```bash
pip install tensorflow numpy pandas matplotlib tqdm
