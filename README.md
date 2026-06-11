# Financial-News-Sentiment-Analysis-WebScraping
Web scraping META news headlines from Yahoo Finance (BeautifulSoup), EDA, data viz, and VADER sentiment analysis (NLP)
Financial News Sentiment Analysis (Web Scraping + NLP)

A data analytics internship project that scrapes live financial news headlines for Meta Platforms (META), cleans and explores the data, visualizes patterns, and runs sentiment analysis using NLP.

Completed as part of the CodeAlpha Data Analytics Internship.

Overview

The project walks through a complete mini data-pipeline in four tasks:


Web Scraping – Collects news headlines from Yahoo Finance using requests and BeautifulSoup, with a fallback sample dataset so the analysis always runs even if the page layout changes.
Exploratory Data Analysis (EDA) – Checks structure, data types, missing values, and duplicates; engineers word-count and character-count features; and detects the most frequent words.
Data Visualization – Plots sentiment distribution, top keywords, and headline-length distribution.
Sentiment Analysis (NLP) – Scores each headline using the VADER lexicon, classifies them as Positive / Neutral / Negative, and surfaces the most positive and most negative headlines for decision-making.


Tech Stack


Python
requests, BeautifulSoup – web scraping
pandas, numpy – data handling
matplotlib, seaborn – visualization
nltk (VADER) – sentiment analysis


How to Run

bashpip install requests beautifulsoup4 pandas numpy matplotlib seaborn nltk

Open CodeAlpha_Internship_Work.ipynb in Jupyter Notebook or Google Colab and run the cells top to bottom.

Output


A custom scraped dataset saved as meta_news_headlines.csv
Charts showing sentiment distribution, top keywords, and headline length
A list of the most positive and most negative headlines


Key Learnings


Building a custom dataset from a live web source
Defensive coding with fallback data
Applying NLP sentiment scoring to real-world financial text
