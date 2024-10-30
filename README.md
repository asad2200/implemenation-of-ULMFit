# Twitter Sentiment Analysis with ULMFiT

This repository contains the code and models for a sentiment analysis project on Twitter airline reviews, utilizing the *ULMFiT (Universal Language Model Fine-tuning)* approach. The goal of this project is to assess the effectiveness of ULMFiT in text classification tasks with limited data, comparing it to a baseline model trained from scratch.

## Project Overview

### Motivation
This project investigates ULMFiT’s ability to perform accurate text classification with minimal labeled data and reduced computational requirements. Traditional models often need large datasets and lengthy training times, but ULMFiT leverages transfer learning by fine-tuning a pre-trained language model on task-specific data, making it an efficient alternative.

### Dataset
We used the *Twitter US Airline Reviews dataset* from Kaggle, which contains labeled sentiment data (positive, negative, neutral) for airline-related tweets.

### Implementation
The project involves:
1.⁠ ⁠*Data Preprocessing*: Cleaning and preparing text data.
2.⁠ ⁠*Baseline Model*: Training an AWD_LSTM model from scratch, achieving an accuracy of 65%.
3.⁠ ⁠*ULMFiT Fine-tuning*: Fine-tuning a pre-trained model using ULMFiT, which increased accuracy to 77%.
4.⁠ ⁠*Evaluation*: Comparison of both models on various performance metrics to validate ULMFiT’s advantages.

## Results
•⁠  ⁠*Baseline Model Accuracy*: 65%
•⁠  ⁠*ULMFiT Model Accuracy*: 77%

The ULMFiT approach demonstrated better accuracy with less data and significantly reduced training time, underscoring the benefits of transfer learning in domain-specific sentiment analysis tasks.

## Getting Started

### Prerequisites
•⁠  ⁠Python 3.7+
•⁠  ⁠Required packages: ⁠ fastai ⁠, ⁠ torch ⁠, ⁠ pandas ⁠, and other dependencies listed in ⁠ requirements.txt ⁠.

## Credits

•⁠  ⁠*Paper Authors: This project is inspired by the paper *"Universal Language Model Fine-tuning for Text Classification" by *Jeremy Howard and Sebastian Ruder* (2018), which introduced the ULMFiT approach and demonstrated its effectiveness in text classification.

•⁠  ⁠*Blog Author: Special thanks to **Rajas Sanjay Ubhare* for his insightful blog post, "Twitter Sentiment Analysis Using ULMFiT" on The Startup, which provided guidance and inspiration for implementing ULMFiT in this project.
