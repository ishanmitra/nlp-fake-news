
# Effectiveness of ML Networks in Classifying Falsified News

This research project explores the effectiveness of various machine learning architectures—such as Convolutional Neural Networks (CNNs), Long Short-Term Memory networks (LSTMs), and Transformers—in identifying and classifying falsified news articles. It has been conducted under the guidance of Brayan Impatá ([@yayaneath](https://github.com/yayaneath)) as part of the AWS AI & ML Scholarship Program.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Aim](#project-aim)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
In today’s era of misinformation, detecting falsified news articles is more critical than ever. This project leverages various neural networks, including CNNs, LSTMs, and Transformers, to classify fake news. By understanding how these networks process textual data, we aim to improve the detection of fake news using state-of-the-art Natural Language Processing (NLP) techniques.

## Dataset
The dataset used for training and evaluation is sourced from Kaggle: [Fake News Detection Dataset](https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection). It contains a collection of news articles labeled as "fake" or "real."

## Project Aim
The goal of this project is to gain a deeper understanding of NLP pipelines. Specifically, how neural networks process text as tokens and how they use vector embeddings to understand the context within sentences. Through this process, we aim to classify news articles as either factual or falsified with high accuracy.

## Technologies Used
- PyTorch
- Natural Language Processing (NLP)
- CNN, LSTM, BERT (Transformer) models
- Kaggle API

## Results
After training the models on the Kaggle dataset, we observed varying levels of performance across the different architectures. Compared to BERT - which is part of the Transformers family, LSTMs exhibited better performance on our specific dataset, particularly in terms of test accuracy.

## Conclusion
Despite the advanced capabilities of Transformers, the LSTM model demonstrated superior performance in classifying fake news on the test dataset. This suggests that, for this particular task and dataset, LSTM’s ability to capture temporal dependencies was more effective than the Transformer model’s attention mechanisms. Further research and experimentation are required to explore why this is the case and to generalize findings across different datasets.
