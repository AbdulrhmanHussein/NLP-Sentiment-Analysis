# NLP-Sentiment-Analysis

## Overview
This project performs sentiment analysis on text data using the BERT model for sequence classification. It processes a dataset with text and category labels, applying extensive text preprocessing and fine-tuning a pre-trained BERT model. The project is implemented in a Google Colab notebook with GPU acceleration and achieves high performance metrics on validation data.

## Features
- Preprocesses text data by lowercasing, removing URLs, HTML tags, emojis, punctuation, and stopwords.
- Utilizes BERT (bert-base-uncased) for sentiment classification with four categories.
- Evaluates model performance using accuracy, precision, recall, and F1-score.
- Implements a custom dataset class and data loaders for efficient training.

## Technologies
- **Languages & Libraries**: Python, pandas, NumPy, scikit-learn, PyTorch, Transformers, NLTK, tqdm
- **Tools**: Google Colab, Jupyter Notebook, GPU (T4)
- **Core Skills**: Natural Language Processing, Deep Learning, Text Preprocessing, Model Fine-Tuning

## Dataset
- Source: Not specified in the notebook (assumed to be a custom dataset or Kaggle dataset with train.csv and test.csv).
- Contains text data (Text column) and sentiment labels (Category column).
- Files: train.csv, test.csv

## Results
- Validation Metrics:
- Accuracy: 0.98125
- Precision: 0.98125
- Recall: 0.98125
- F1 Score: 0.98123
- Training completed in 3 epochs with a batch size of 16, using AdamW optimizer (learning rate: 5e-5).
