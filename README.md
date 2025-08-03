# Stock News Summarizer & Sentiment Tracker

This project provides an easy way to **summarize financial news** about stocks and analyze the **sentiment of recent articles**.  
Its goal is to help you better track your investment portfolio by quickly understanding the market mood around your stocks.

## Features
- Summarizes the latest stock-related news articles  
- Performs sentiment analysis (positive, neutral, negative)  
- Helps track and evaluate stock performance through news sentiment  

## Models Used
- **Summarizer model: Facebook bart (limit of only 1024 tokens) for bigger models just change the path inside the notebook**  
- **Sentiment analysis model: Finbert**  

## Currently required APIs (free)
As long as the webscraper is not optimzed, the free API of https://newsapi.org/ is used

## Requirements
- Python 3.9 or higher  
- At least 8 GB RAM (depending on the size of the summarizer model) recommended for smooth processing  
- Internet connection (to fetch news articles)

## Issues
Summarizer doesn't work properly
webscraper does it job but still facing issues with extracting proper data


