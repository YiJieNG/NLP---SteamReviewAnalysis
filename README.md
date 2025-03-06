# NLP---SteamReviewAnalysis

## Overview
This project aims to analyze and cluster multilingual Steam game reviews using multilingual BERT (mBERT) for word embeddings and unsupervised clustering techniques. The goal is to identify patterns in language distribution, sentiment polarity, and player engagement styles across different game reviews.

🔍 Key Objectives
- Text Processing & Embedding: Preprocess Steam reviews in multiple languages.
- Use mBERT (Hugging Face Transformers) to generate word embeddings for clustering.
- Unsupervised Clustering: Apply clustering algorithms to group reviews based on linguistic similarity and sentiment patterns.
- Identify common themes across different clusters and analyze the distribution of languages in each group.

## Dataset Link
Dataset : www.kaggle.com/datasets/lucaspoo/steam-reviews-international/data

## Challenges
It took significant time to run the feature extraction using mBERT transformer since we are using a large dataset. To address this, several strategies are applied to reduce the running time:
Resource: Switch from solely depends on CPU to CUDA core using RTX 3060
Optimisation technique applied: Batching

As a result, the running time has decreased significantly from more than 7 hours to 1.5 hours.

## Evaluation
Find out more about the result at: https://www.ngyijie.com/projects/steamReviewAnalysis
