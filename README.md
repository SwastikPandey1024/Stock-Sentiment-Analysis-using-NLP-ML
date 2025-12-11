# Stock-Sentiment-Analysis-using-NLP-ML
A machine learning project that analyzes 108k+ stock-related tweets using NLP techniques like NER, VADER sentiment scoring, and TF-IDF. A Random Forest model (≈78% accuracy) predicts tweet sentiment and links it to stock stability or volatility, offering actionable insights for market trend analysis.




## **📌 Stock Sentiment Analysis Using NLP & Machine Learning**

This project analyzes **108,750 stock-related tweets** using advanced **Natural Language Processing (NLP)** and **Machine Learning** techniques to predict market sentiment and assess potential stock behavior.

### 🔍 **What the Project Does**

* Cleans and preprocesses noisy tweet data (removes URLs, hashtags, stopwords, etc.)
* Extracts financial entities using **Named Entity Recognition (spaCy)**
* Performs sentiment scoring using **VADER**
* Converts text into numerical vectors using **TF-IDF**
* Trains ML models (Logistic Regression & Random Forest) for sentiment classification

### 📈 **Key Results**

* **Random Forest Accuracy:** ~78%
* Strong precision/recall balance with an F1-score around 80%
* Positive sentiment correlates with **stable, low-volatility stocks**
* Negative or fluctuating sentiment indicates **high-risk, volatile stocks**

### 🧠 **Impact**

This project demonstrates how real-time social media sentiment can support:

* Early volatility detection
* Risk categorization
* Smarter trading decisions
* Sentiment-driven financial insights

### 🚀 **Tech Stack**

Python • NLP (spaCy, NLTK) • VADER • TF-IDF • RandomForestClassifier • Google Colab

