# LLM Output Evaluation (Intro)

This repository contains a Jupyter notebook providing a foundational guide to essential evaluation metrics for Artificial Intelligence (AI) outputs. It covers practical implementations for both **labeling (classification)** and **text generation** tasks.

## 📋 Table of Contents
- [Key Evaluation Metrics](#key-evaluation-metrics)
    - [Classification (Labeling)](#1-classification-labeling)
    - [Text Generation](#2-text-generation)
- [Installation & Dependencies](#installation--dependencies)


## 🧪 Key Evaluation Metrics
<img width="1621" height="1082" alt="image" src="https://github.com/user-attachments/assets/85274b0d-2f74-4d98-9894-daa94626f9b0" />



### 1. Classification (Labeling)
For tasks where the model categorizes or labels data, the notebook demonstrates:
* **Confusion Matrix**: A visualization tool used to compare predicted classifications against actual ground truth
* **Precision, Recall, and F1-Score**: Core statistical measures to assess classification accuracy.

### 2. Text Generation
For tasks such as summarization or translation, the notebook implements:
* **BLEU (Bilingual Evaluation Understudy)**: Evaluates the overlap of n-grams between generated and reference text.
* **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**: Primarily used for summarization, focusing on how much of the reference text is captured by the model.
* **BERTScore**: A modern metric that utilizes pre-trained BERT embeddings to measure semantic similarity, moving beyond simple word-matching.

## 🛠 Installation & Dependencies
To run the evaluation examples, you will need to install the following Python packages:

```bash
pip install scikit-learn nltk rouge-score bert-score


## You also need OpenAI API key to run some parts of code. 
