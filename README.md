# Sentiment Analysis Using Deep Learning Models

## Project Description

This project focuses on performing sentiment analysis on tweets from the Sentiment140 dataset using deep learning techniques. We implemented and compared:

- **Baseline models:**
  - Random baseline (randomly predicts labels)
  - Most frequent baseline (always predicts the most common label)
  - A Bi-LSTM (Bidirectional Long Short-Term Memory) model

- **Proposed model:**
  - A fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model

The goal was to evaluate the effectiveness of advanced transformer-based architectures compared to simpler recurrent neural networks and naive baselines for sentiment classification tasks.

The project demonstrates that fine-tuning pre-trained transformers like BERT significantly outperforms traditional deep learning models and naive baselines, especially when handling noisy, informal social media text.

---

## Requirements

Please make sure the following packages are installed:

- `torch`
- `transformers`
- `nltk`
- `scikit-learn`
- `pandas`
- `numpy`

You can install them using:

```bash
pip install torch transformers nltk scikit-learn pandas numpy
