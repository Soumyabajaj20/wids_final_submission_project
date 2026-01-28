# wids_final_submission_project
NVIDIA STOCK NEWS DATA PIPELINE

Overview
This project collects and processes news headlines related to NVIDIA stock using Google News RSS feeds.
The main goal is to convert raw, unstructured news data into a clean and structured dataset that can be used for analysis such as sentiment analysis or financial research.

# Project Objective

 -  Fetch NVIDIA stock related news automatically

 - Extract useful information from RSS feeds

 - Clean and organize the data

 - Store the processed data in CSV format for further use

 # Technologies Used

 - Python

 - Requests

 - BeautifulSoup

 - Pandas

 - NumPy

 # Project Files

midterm_submission.ipynb : Main notebook containing the full workflow

news_raw.csv : Raw news data collected from RSS feeds

news_cleaned.csv : Cleaned and processed news dataset

README.md : Project description

 # How the Project Works

**Step 1: News Collection**
The program fetches NVIDIA stock news using Google News RSS feeds.
From each news item, it extracts:

 - News source

 - Headline

 - Publication date

*The raw extracted data is saved as news_raw.csv.*

**Step 2: Data Cleaning**
The raw data is cleaned and processed by:

 - Converting publication dates to a standard format

 - Removing unnecessary characters

 - Adding a headline length feature

*The final cleaned dataset is saved as news_cleaned.csv.*

 # Output Data Description

news_cleaned.csv contains the following columns:

source : Name of the news publisher

headline : News headline text

pubdate : Date of publication

headline_length : Number of characters in the headline

 # How to Run

Install required libraries:
pip install requests pandas numpy beautifulsoup4

Open and run:
main_code.ipynb

 # Use Cases

 - Financial news analysis

 - Sentiment analysis on stock-related headlines

 - Event-based market research

 - Academic or coursework submission
