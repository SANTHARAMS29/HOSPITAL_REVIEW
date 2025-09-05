🧠 Patient Sentiment Analysis Using NLP & LLMs

This project analyzes open-ended patient reviews to predict sentiment (positive or negative) using Natural Language Processing (NLP) techniques and Large Language Models (LLMs).

🚀 Project Overview

Goal: Classify patient feedback based on sentiment
Dataset: 996 hospital reviews with labeled sentiment
Techniques used:
Text cleaning and preprocessing (NLTK, regex)
Exploratory Data Analysis (word clouds, word frequencies, review length)
Feature extraction with TF-IDF
Sentiment classification using:
Logistic Regression (baseline)
distilBERT LLM from Hugging Face (zero-shot)


📊 Results Summary

Logistic Regression (TF-IDF)
Accuracy: 0.86
High precision on positive class
Poor recall on negative class

distilBERT (LLM)
Accuracy: 0.78
Much better at identifying negative reviews
Balanced recall across classes

🛠️ Tech Stack

Python, Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn
Hugging Face Transformers (distilBERT)
Google Colab (for LLM execution)

📁 How to Run

Open MODELLING AND LLM COMPARISION.ipynb in Google Colab
Mount your Google Drive and upload the cleaned dataset (or use the one provided)
Run the cells to explore, train, and evaluate both models
