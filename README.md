# Metis-Emoji-Analysis
### Code for the emoji complexity analysis done for Metis Project 03

This repo contains code I used for my emoji complexity analysis. 

- **emoji_analysis.ipynb** - A Jupyter notebook with code to query a Mongo database of tweets, train a word vector model on the corpus, split out the emoji and text, and measure the complexity of emoji usage per tweet

- **twitter_scrape.py** - Python script using the Twitter API to scan streaming tweets for any tweets with emoji in them, storing them all in a Mongo database
