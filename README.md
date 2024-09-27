# ML-for-NLP

Sentiment Analysis NLP project by Jules Kuperminc and Etienne Maeght

Course: [Machine Learning for Natural Language Processing](https://nlp-ensae.github.io) at [ENSAE Paris](https://www.ensae.fr)

## Methods

Our purpose was to try various methods for sentiment analysis on a small dataset and to interpret performance.

- Bag-of-words:
  - Random Forest classification
  - Random Forest with rebalanced set
  - Weighted Random Forest
  - Random Forest with a restricted number of features
  - Linear Discriminant Analysis
  - Linear Discriminant Analysis with a restricted number of features
  - Support Vector Classification
  - Support Vector Classification with a rstricted number of features
- Word2Vec Embedding [Fasttext](https://fasttext.cc) pretrained on Wikipedia-english
  - Neural Network with one hidden layer
  - LSTM
- transformer BERT (tiny) pretrained [here](https://huggingface.co/prajjwal1/bert-tiny)

## Data

- [Amazon Alexa reviews](https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews)
- [Amazon Review Data](https://nijianmo.github.io/amazon/index.html)
  > Justifying recommendations using distantly-labeled reviews and fined-grained aspects, Jianmo Ni, Jiacheng Li, Julian McAuley, Empirical Methods in Natural Language Processing (EMNLP), 2019

## Files

- Synthetic report [ML_for_NLP_Kuperminc_Maeght.pdf](./ML_for_NLP_Kuperminc_Maeght.pdf)
- All the relevant code is in [Amazon_Reviews_Sentiment_Analysis_Jules_Kuperminc_Etienne_Maeght.ipynb](./Amazon_Reviews_Sentiment_Analysis_Jules_Kuperminc_Etienne_Maeght.ipynb)
