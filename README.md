# Sentiment Analysis on Amazon Reviews 🛒📝
This project performs sentiment analysis on Amazon product reviews using a blend of traditional rule-based and state-of-the-art transformer-based NLP models. The goal is to classify reviews as positive, negative, or neutral by leveraging different approaches to capture sentiment nuances.

# Features
Multi-Method Approach:
  Rule-based sentiment scoring with VADER ⚖️ for fast baseline analysis
  Fine-tuned RoBERTa transformer 🤖 for deep contextual understanding
  Hugging Face Transformers library 🌟 for advanced sentiment classification

Data Preprocessing:

Text cleaning, tokenization, and normalization to prepare raw reviews for analysis

Handling of neutral, positive, and negative classes for balanced sentiment classification

Model Evaluation:

Comparison of models based on accuracy, precision, recall, and F1-score

Visualization of sentiment distribution and model performance metrics

Getting Started
Prerequisites
Python 3.x

Required libraries: transformers, nltk, pandas, scikit-learn, torch

You can install dependencies via:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Open the Jupyter notebook (.ipynb) or run the Colab notebook to explore the full workflow

The notebook contains step-by-step cells covering data loading, preprocessing, model training, and evaluation

Modify the notebook to experiment with different datasets or tweak model parameters

Project Structure
bash
Copy
Edit
/SentimentAnalysis-AmazonReviews
│
├── Sentiment_Analysis_Amazon_Reviews.ipynb    # Main notebook with all steps
├── requirements.txt                           # Required Python packages
├── README.md                                 # This file
└── data/                                     # Sample datasets or links (if any)
About Me
I am Vansh, a passionate student at NSUT, exploring AI and NLP through practical projects like this sentiment analysis model. This project reflects my growing expertise in natural language processing, transformer models, and data-driven insights.

License
This project is licensed under the MIT License.
