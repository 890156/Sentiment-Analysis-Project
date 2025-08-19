# Sentiment-Analysis-Project

# AI Sentiment Analyzer (Colab & Terminal)

This is a simple interactive program that analyzes the sentiment (Positive / Negative / Neutral) of sentences using **TextBlob**.  

Features:
- Color output in terminal (via `colorama`).  
- HTML-colored output automatically when running in **Google Colab**.  
- Saves results to `sentiment_results.csv`.  

## Setup (Local)
```bash
pip install -r requirements.txt
python -m textblob.download_corpora
python sentiment_analyzer.py
