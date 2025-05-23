# Text Classification - Sentiment Analysis

## Overview

This repository contains the implementation of several models for the novel task of binary text classification. The models categorizes text documents into predefined labels. It leverages modern machine learning and natural language processing (NLP) techniques to achieve high accuracy and scalability

## Datasets

The Airline dataset contains approximately 50 000 Reviews scraped from airlinequality.com. The idea was inspired by the approach of *Maas et al., 2011* where 50 000 movie reviews from imdb.com were scraped in order to have more robust benchmark for the task of Sentiment Analysis. As the movie dataset, the document contains an even number of negative and positive reviews. The threshold where a review is regarded as 'negative' is set to ≤ 4 and for positive reviews to ≥ 7, just as the aforementioned paper, as both review sites use the same rating system. These preliminary considerations where taken into account to ensure comparability.

The second dataset contains 3000 german reviews from trustpilot.com on an online fashion retailer. The number of negative and positive reviews are even and the same threshold for classifying a review positive or negative was employed.

## Features

Several models where trained by either fully training/fine-tuning or few-shot learning:

- Classical Machine Learning
    - Naive Bayes
    - Logistic Regression
    - Support Vector Machines 
- Pretreained Language Model
    - BERT

## Citations
1. Maas, A. L., Daly, R. E., Pham, P. T., Huang, D., Ng, A. Y., & Potts, C. (2011). 
   Learning word vectors for sentiment analysis. *Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies*, 142–150. 
   [Link to paper](https://aclanthology.org/P11-1015/)
