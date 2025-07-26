# 🧠 Tweet Sentiment Analyzer

A Natural Language Processing (NLP) project that analyzes the sentiment of tweets using a dataset (CSV) containing raw tweet texts. It uses TextBlob for sentiment classification and visualizes the results using matplotlib.

---

## 🎯 Objective of the Task

The goal of this project is to analyze public sentiment from tweets by building a simple but effective sentiment analysis pipeline. This can help in understanding public opinion on events, brands, or hashtags.

### What the pipeline does:
- Loads tweets from a CSV file
- Cleans and preprocesses the text
- Applies sentiment analysis using TextBlob
- Visualizes positive, negative, and neutral sentiment counts

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **pandas** – for data handling
- **nltk** – for stopword removal
- **textblob** – for sentiment scoring
- **matplotlib** – for data visualization

---

## 🧪 Methodology / Approach

1. **Preprocessing**:
   - Lowercasing
   - Removing punctuation
   - Removing stopwords

2. **Sentiment Scoring**:
   - TextBlob calculates polarity of each tweet
   - Classified as Positive, Negative, or Neutral

3. **Visualization**:
   - A bar chart shows the count of each sentiment type

---

## 📁 Dataset

- The project uses a CSV file named `tweets.csv`
- It must contain a column named `text` with raw tweet content

---

## 📈 Key Results / Observations

- Majority of tweets were classified as **positive**, suggesting an overall favorable sentiment trend.
- A significant number of tweets were **neutral**, indicating objective or ambiguous language.
- **Negative tweets** were less frequent but still present, useful for identifying criticism or dissatisfaction.

---

## 💡 Skills Gained

- Data cleaning and text preprocessing using NLTK
- Sentiment analysis using TextBlob
- Data visualization using Matplotlib
- Understanding of NLP pipeline structure
- Working with CSV data in Python
- Structuring machine learning projects for GitHub

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python sentiment_analysis.py
