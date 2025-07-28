# IMDb Movie Review Sentiment Classifier

This project is a binary text classifier that predicts whether a movie review is **positive** or **negative**, built using TensorFlow and the **Universal Sentence Encoder** from TensorFlow Hub.

## Features

- Trained on the IMDb Reviews dataset (25k training, 25k test)
- Uses pretrained sentence embeddings from `tensorflow-hub`
- Achieves ~79.82% test accuracy
- Provides custom review predictions
- Plots training/validation accuracy and loss

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/imdb-sentiment-classifier.git
cd imdb-sentiment-classifier
