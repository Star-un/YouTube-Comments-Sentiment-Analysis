# YouTube Comments Sentiment Analysis

## Overview
This project performs sentiment analysis on YouTube comments to understand audience emotion (positive, negative, neutral) using simple natural language processing tools in Python.

## Dataset
- Source: [YouTube Comments Dataset (45k rows) - Kaggle](https://www.kaggle.com/datasets/mehtaakshat/youtube-comments-data-sentiment-toxicity-spam)
- Description: A collection of YouTube comments labeled with metadata; used here to analyze overall sentiment distribution.

## What I Did
- Loaded and cleaned YouTube comment text (removed missing and empty comments).
- Used **TextBlob** and **VADER** to assign sentiment labels (Positive / Negative / Neutral).
- Compared the results and created visualizations to show sentiment distribution and examples of top positive comments.

## Tools Used
- Python
- Pandas (data loading and cleaning)
- TextBlob (simple sentiment analysis)
- VADER (lexicon‑based sentiment analysis)
- Matplotlib / Seaborn (visualization)
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Place the dataset CSV file in the `data/` folder (or update the path in the notebook).
3. Open `youtube_comments_sentiment_analysis.ipynb` in Jupyter and run the cells.

## Example Output
- Pie and bar charts showing sentiment distributions.
- A list of sample positive comments.
