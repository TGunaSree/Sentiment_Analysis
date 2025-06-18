Sentiment Analysis for Restaurant Review Data
Overview

This project performs sentiment analysis on restaurant review data. The goal is to classify customer reviews as positive, negative.

Features
Preprocessing of raw restaurant review text
Exploratory Data Analysis (EDA) to understand review trends
Review sentiment classification using machine learning models
Visualizations of sentiment distribution
Dataset

The dataset consists of customer reviews collected from various restaurant platforms. Each entry includes a review text and its associated sentiment label.

Usage

Clone the repository

bash<button><svg><path></path></svg><span>Copy code</span><span></span></button>
git clone https://github.com/TGunaSree/Sentiment_Analysis.git
cd Sentiment_Analysis

Run the notebook

Open and execute Sentiment_Analysis_.ipynb in Jupyter Notebook.

Requirements

Python 3.x
pandas, numpy, scikit-learn, matplotlib, seaborn, nltk

Install requirements with:

bash<button><svg><path></path></svg><span>Copy code</span><span></span></button>
pip install -r requirements.txt

How it works

The notebook walks through data cleaning, feature extraction (TF-IDF or word embeddings), model selection (such as Logistic Regression or Naive Bayes), evaluation, and visualization of the results.
Results

The output includes model performance metrics (accuracy, precision, recall) and visualizations showing the distribution of sentiments in the review data.

