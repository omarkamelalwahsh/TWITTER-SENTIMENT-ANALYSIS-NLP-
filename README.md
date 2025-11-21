# TWITTER-SENTIMENT-ANALYSIS-NLP-
https://www.kaggle.com/datasets/kazanova/sentiment140
## Overview
This project predicts the **sentiment of tweets** as **Positive (1)** or **Negative (0)** using **Machine Learning** and **Natural Language Processing (NLP)** techniques.

It leverages:
- Text cleaning and preprocessing
- TF-IDF feature extraction
- Linear Support Vector Classifier (LinearSVC)

## Dataset
- **Sentiment140 Dataset**: 1.6 million tweets
- Columns:
  - `target`: sentiment label (0 = Negative, 4 converted to 1 = Positive)
  - `id`, `date`, `flag`, `user`, `text`
- Dataset is loaded from `training.1600000.processed.noemoticon.csv` and preprocessed.
