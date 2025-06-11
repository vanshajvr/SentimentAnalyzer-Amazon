# Sentiment Analysis on Amazon Reviews 🛒📝
This project performs sentiment analysis on Amazon product reviews using a blend of traditional rule-based and cutting-edge transformer-based NLP models. The goal? Classify reviews as positive, negative, or neutral by leveraging diverse methods to capture the full sentiment spectrum. 🔍✨

> **Note:** A fully interactive Google Colab notebook is linked below for a hands-on experience without any setup! 🚀☁️

# Features 🚀
  # Multi-Method Approach:
  - Rule-based sentiment scoring with VADER ⚖️ for fast baseline analysis
  - Fine-tuned RoBERTa transformer 🤖 for deep contextual understanding
  - Hugging Face Transformers library 🌟 for advanced sentiment classification

  # Data Preprocessing:
  - Text cleaning, tokenization, and normalization 🧹 to prep raw reviews
  - Balanced handling of positive, negative, and neutral sentiments ⚖️
  # Model Evaluation:
  - Accuracy, precision, recall, and F1-score metrics 📊
  - Visualizations of sentiment distribution and performance 📈

# Getting Started 🛠️

# Prerequisites
  - Python 3.x
  - Libraries: transformers, nltk, pandas, scikit-learn, torch

# Install dependencies with:
    pip install -r requirements.txt

#  Dataset 📂: 
- This project uses the [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) dataset from Kaggle.
- Contains 568,000+ food reviews from Amazon, including ratings, review text, and product info 🛒
- Ideal for natural language processing and sentiment classification tasks
- Download it manually and place the CSV file in a data/ folder before running the notebook.

# Usage
  - Open the Jupyter/Colab notebook (.ipynb) to follow the full workflow 📓
  - Step-by-step cells cover data loading, preprocessing, model training, and evaluation
  - Feel free to tweak parameters or try your own datasets! 🔧

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qKUJKs7MVxVTKZNvdk72NBT9Xn_oqnve?usp=sharing)

# Project Structure
    /SentimentAnalysis-AmazonReviews
    │
    ├── Sentiment_Analysis_Amazon_Reviews.ipynb    # Main notebook with complete workflow
    ├── requirements.txt                           # Python package dependencies
    ├── README.md                                 # This file
    └── data/                                     # Sample datasets or data links

# About Me ✨
Hi, I’m Vansh, a passionate NSUT student exploring AI & NLP through hands-on projects like this one. This repo showcases my growing skills in natural language processing, transformer models, and data-driven insights. 🚀

# License ⚖️
This project is licensed under the MIT License.
