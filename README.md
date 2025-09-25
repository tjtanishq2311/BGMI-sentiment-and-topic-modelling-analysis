BGMI Sentiment and Topic Modelling Analysis
📌 Overview

This project performs sentiment analysis and topic modeling on Battlegrounds Mobile India (BGMI) user reviews. The aim is to analyze how the gaming community perceives BGMI, uncover trending discussion topics, and visualize insights from textual data.

The notebook uses NLP and machine learning techniques such as:

Text preprocessing (tokenization, stopwords removal, lemmatization)

Sentiment Analysis with TextBlob

Topic Modelling with NMF (Non-negative Matrix Factorization) and TF-IDF

Data visualization with Matplotlib

⚡ Features

Import and preprocess user reviews dataset (.xlsx file).

Perform sentiment analysis (positive, neutral, negative).

Extract key topics from reviews using TF-IDF + NMF.

Visualize results through charts and word distributions.

Generate actionable insights about player feedback.

🛠️ Tech Stack

Python

Libraries:

pandas, numpy (data handling)

nltk (text preprocessing)

textblob (sentiment analysis)

sklearn (TF-IDF, NMF)

matplotlib (visualization)

📂 Project Structure
📁 BGMI-Sentiment-Topic-Analysis
│── gba_2025.ipynb       # Main Jupyter Notebook
│── data.xlsx            # Input dataset (user reviews)
│── README.md            # Project documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/BGMI-Sentiment-Topic-Analysis.git
cd BGMI-Sentiment-Topic-Analysis


Install dependencies:

pip install pandas numpy matplotlib nltk textblob scikit-learn openpyxl


Open the Jupyter Notebook:

jupyter notebook gba_2025.ipynb


Run all cells step by step to:

Load dataset

Preprocess text

Run sentiment analysis

Perform topic modeling

Visualize insights

📊 Results

Distribution of sentiments (positive / neutral / negative)

Extracted topics with top keywords

Visualizations for sentiment and topics

📌 Future Scope

Use advanced models like VADER, BERT, or RoBERTa for sentiment analysis.

Experiment with LDA or BERTopic for improved topic modeling.

Deploy as a web dashboard using Streamlit or Flask.
