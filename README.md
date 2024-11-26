# Text Classification - Sentiment Analysis

## Overview

This repository contains the implementation of a Text Classification system that categorizes textual data into predefined labels. It leverages modern machine learning and natural language processing (NLP) techniques to achieve high accuracy and scalability

## Dataset

The dataset contains approximately 50 000 Reviews scraped from airlinequality.com. The idea was inspired by the approach of *Maas et al., 2011* where 50 000 movie reviews from imdb.com were scraped in order to have more robust benchmark for the task of Sentiment Analysis.

## Features

Several models where trained by either fully training/fine-tuning or few-shot learning:

- Classical Machine Learning
    - Naive Bayes
    - Logistic Regression
    - Support Vector Machines 
- Deep Learning Approach
    - RNN-LSTM
    - RNN-GRU
        - including Word Embeddings using GloVe and Word2Vec
    - GCN
- Large Language Models
    - BERT
    - T5 and Flan-T5 
- Few-Shot Learning
    - GPT-4
    - Llama 3.1
    - Mistral
    - Gemma:7b

## Citations
1. Maas, A. L., Daly, R. E., Pham, P. T., Huang, D., Ng, A. Y., & Potts, C. (2011). 
   Learning word vectors for sentiment analysis. *Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies*, 142–150. 
   [Link to paper](https://aclanthology.org/P11-1015/)
