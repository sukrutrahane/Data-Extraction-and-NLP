# Data-Extraction---NLP
## Text Analysis &amp; Extraction of textual data articles from the given URLs from Excel Sheet.

## Data Extraction (Using BeautifulSoup):
Step 1: Use requests library to fetch the HTML content from the given URL.
Step 2: Parse the HTML content using BeautifulSoup.
Step 3: Identify and extract the relevant text data (articles) from the HTML.

import requests
from bs4 import BeautifulSoup

## Text Analysis:
Step 4: Perform text analysis on the extracted data using natural language processing (NLP) techniques.
Step 5: Compute the required variables, which may include:
Word count
Frequency distribution of words
Sentiment analysis
Named Entity Recognition (NER)
etc.

import nltk
from nltk.tokenize import word_tokenize
from nltk.probability import FreqDist
from nltk.sentiment import SentimentIntensityAnalyzer
import spacy

