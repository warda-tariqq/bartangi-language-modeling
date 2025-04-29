# Bartangi Language Modeling Resources

This repository contains code and resources for building a clean Bartangi language corpus, performing morphological lemmatization, training word embeddings (Skip-gram and CBOW), and visualizing embeddings for low-resource language modeling tasks.

## 📚 Project Overview

- Data Collection and Cleaning
- Morphological Analysis (Lemmatization)
- Word Embedding Training (Word2Vec: CBOW and Skip-gram)
- Embedding Visualization (PCA and t-SNE)
- Corpus preparation for future low-resource NLP tasks

## 🚀 Getting Started

### Requirements

Install Python 3.8+ and the required libraries:

```bash
pip install -r requirements.txt
Running the Pipeline
Preprocess the Raw Corpus
python scripts/preprocess.py
Lemmatize the Corpus
python scripts/lemmatize.py
Train Word Embeddings
python scripts/train_embeddings.py
Visualize Embeddings
PCA and t-SNE plots will be saved in the outputs/ folder.

We used the publicly available Bartangi corpus by Arseniy Novokshanov for initial data collection.

Note: The raw corpus is not included in this repository.
Please refer to the original source for accessing it.
