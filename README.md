# Twitter Sentiment Analysis

A **Natural Language Processing (NLP)** project to detect the sentiment of tweets as **positive, neutral, or negative**. This project uses **TF-IDF feature extraction** and **Logistic Regression**, and it can be extended to advanced models like **BERT** for better accuracy.

---

## **Table of Contents**

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Technologies & Libraries](#technologies--libraries)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Future Enhancements](#future-enhancements)  
- [Author](#author)

---

## **Project Overview**

This project focuses on analyzing **Twitter data** to classify the sentiment of tweets into three categories:

- **Positive**  
- **Neutral**  
- **Negative**

The workflow includes:

1. Loading and cleaning the dataset  
2. Text preprocessing (removing stopwords, URLs, mentions, hashtags, special characters)  
3. Feature extraction using **TF-IDF**  
4. Training a **Logistic Regression** classifier  
5. Evaluating the model with accuracy, precision, recall, F1-score, and confusion matrix  
6. Deploying a simple interface to test new tweets

---

## **Dataset**

We use the **[Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)**:

- 1,600,000 tweets  
- Sentiment labels:
  - `0` = Negative  
  - `2` = Neutral  
  - `4` = Positive  

**Note:** The dataset is in `latin-1` encoding and does not contain headers by default.

---

## **Features**

- Text preprocessing:
  - Lowercasing  
  - Removing URLs, mentions, hashtags, and special characters  
  - Removing stopwords  
  - Lemmatization  

- Feature extraction:
  - TF-IDF (Term Frequency-Inverse Document Frequency)  

- Classification:
  - Logistic Regression (baseline)  
  - Can be extended to Word2Vec, BERT, or other transformers  

---

## **Technologies & Libraries**

- **Python 3.10+**  
- Libraries:
  - `pandas`  
  - `numpy`  
  - `nltk`  
  - `scikit-learn`  
  - `matplotlib` / `seaborn`  
  - `pickle` (for saving models)  

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Twitter-Sentiment-Analysis.git
cd Twitter-Sentiment-Analysis
