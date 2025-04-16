Bitcoin Price Prediction & Influencer Correlation
This project explores the relationship between social media influence and Bitcoin price movements using data science and machine learning. The analysis covers Twitter sentiment data and prominent cryptocurrency influencers, alongside historical Bitcoin data and technical indicators. In combination with sentiment analysis, a good ML model like LSTM or Linear Regression for shorter timespan can serve as a tool for predicting Bitcoin price. This project works only for a certain period - 05.02.2021 to 12.03.2021, but could be integrated for realtime, using paid Twitter API.

Project Structure:
data_preparation.ipynb
Loads a dataset of Bitcoin-related tweets from Kaggle(from 05.02.2021 to 12.03.2021) and prepares it for sentiment analysis and further modeling.

correlation_finding.ipynb
Checks for correlations between their sentiment and Bitcoin prices.

bitcoin_price_prediction.ipynb
Processes Bitcoin price data, adds technical indicators, and performs predictions using the prepared features.

influencers.py
Contains a list of the top 100 crypto influencers used for filtering relevant tweets.

All required Python packages to run the notebooks:
pandas>=2.2.3  
numpy>=2.0.2  
yfinance>=0.2.54  
matplotlib>=3.8.4  
scikit-learn>=1.6.1  
transformers>=4.51.3  
torch>=2.2.2

📊 Data Sources:
Bitcoin Prices: Collected via yfinance.
Tweets: Dataset from Kaggle (Bitcoin_tweets.csv), https://www.kaggle.com/code/codeblogger/bitcoin-sentiment-analysis/input.

How to Run:
Clone the repo: 
git clone https://github.com/zarkobeats/bitcoin_sentiment_analsyis.git
cd project

Install dependencies:
pip install -r requirements.txt

Open and run the notebooks in order:
data_preparation.ipynb
correlation_finding.ipynb
bitcoin_price_prediction.ipynb

Technologies Used:
Python
Jupyter Notebook
Pandas, NumPy, Scikit-learn
Transformers (for NLP/sentiment modeling)
yFinance, Matplotlib

Note:
This project is for educational and research purposes only. Cryptocurrency markets are volatile, and predictions based on public data and sentiment should not be used for financial decisions without proper validation.

