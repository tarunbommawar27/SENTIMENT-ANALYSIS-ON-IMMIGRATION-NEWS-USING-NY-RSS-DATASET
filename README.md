# NYT News Sentiment Analysis and Topic Modeling

This project analyzes news articles from the New York Times **World News RSS Feed** to extract insights about media sentiment and topic trends. It uses techniques like **sentiment analysis**, **topic modeling**, and **time-based trends** visualization.

---

## 📋 Project Description

The goal of this project is to analyze the tone and themes of news articles related to global events. The project cleans, processes, and visualizes news data using Python-based tools, focusing on:

1. **Sentiment Analysis**: Classify articles as `Positive`, `Negative`, or `Neutral` based on their descriptions.
2. **Topic Modeling**: Identify key themes in the article content using natural language processing.
3. **Time-Based Analysis**: Visualize how sentiment trends evolve over time.
4. **Word Cloud Generation**: Highlight the most frequent terms in the news descriptions.

---

## 📂 Data Source

- **Source**: [New York Times RSS Feed](https://www.nytimes.com/interactive/2021/us/new-york-times-rss-feeds.html)
- **Feed URL**: `https://rss.nytimes.com/services/xml/rss/nyt/World.xml`

The RSS feed provides structured metadata for each article, including:
- `Title`: Headline of the article.
- `Description`: A short summary of the article.
- `Published_Date`: The date and time the article was published.

---

## 🚀 How to Run the Project

### Prerequisites
- Python 3.x installed.
- Libraries: `pandas`, `nltk`, `matplotlib`, `wordcloud`, `textblob`, `gensim`, `spacy`.

Install required libraries using:
```bash
pip install pandas nltk matplotlib wordcloud textblob gensim spacy
