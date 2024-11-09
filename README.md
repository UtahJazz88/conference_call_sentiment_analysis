# conference_call_sentiment_analysis
# Conference Call Sentiment Analysis Project

## Project Overview
This project analyzes conference call transcripts from corporate earnings calls, focusing on sentiment analysis to examine the relationship between management communication and market performance.

## Key Components

1. Data Collection
- `01transcript_scraper.ipynb`: Conference call transcript collection
- `02Conference Earning Call Scraper.ipynb`: Earnings call data scraping
- `transcript_scraper.ipynb`: Additional data collection tools

2. Data Preprocessing
- `03Split Pre QA Participants.ipynb`: Separates Q&A sections and participant information
- `03Split Pre QA Participants - operator.ipynb`: Data processing by operator sections
- `05Merge XandY Data For Regression.ipynb`: Merges X and Y data for regression analysis

3. Sentiment Analysis
- `04sentiment tone analysis.ipynb`: Text sentiment tone analysis
- `sentiment-analysis-s-p-500.ipynb`: S&P 500 companies sentiment analysis
- `non ceo finbert general.ipynb`: Non-CEO text analysis using FinBERT

4. Regression Analysis
- `06Regression.ipynb`: Base regression analysis
- `06Regression_new.ipynb`: Updated regression models
- `06Regression_new_nonfin.ipynb`: Non-financial companies regression
- `07LMRegression.ipynb`: LM regression models
- `07-2LM re new.ipynb`: FinBert regression analysis
