# 📈 Bitcoin Price Prediction & Influencer Correlation

This project explores the relationship between social media influence and Bitcoin price movements using data science and machine learning. We analyze Twitter sentiment from key cryptocurrency influencers alongside historical Bitcoin data and technical indicators to build predictive models.

> **Note:** This project focuses on a specific time window — **February 5, 2021 to March 12, 2021** — but it can be extended for real-time analysis using the Twitter API (paid access required).

---

## 🗂️ Project Structure

- **`data_preparation.ipynb`**  
  Loads and cleans Bitcoin-related tweets from Kaggle, preparing them for sentiment analysis and modeling.

- **`correlation_finding.ipynb`**  
  Analyzes the correlation between Twitter sentiment and Bitcoin price movements.

- **`bitcoin_price_prediction.ipynb`**  
  Builds models (LSTM, Linear Regression) to predict Bitcoin price using sentiment and technical indicators.

- **`influencers.py`**  
  Contains a curated list of the top 100 cryptocurrency influencers to filter relevant tweets.

---

## 🛠 Technologies Used

- **Programming**: Python
- **Environment**: Jupyter Notebook
- **Libraries**:  
  - `pandas`, `numpy` – Data manipulation  
  - `scikit-learn` – Machine learning  
  - `transformers`, `torch` – NLP & sentiment analysis  
  - `yfinance` – Historical financial data  
  - `matplotlib` – Visualization

---

## 📊 Data Sources

- **Bitcoin Prices**: [Yahoo Finance](https://finance.yahoo.com) (via `yfinance`)
- **Tweet Dataset**: [Kaggle - Bitcoin Sentiment Analysis](https://www.kaggle.com/code/codeblogger/bitcoin-sentiment-analysis/input)

---

## 🔧 Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/zarkobeats/bitcoin_sentiment_analsyis.git
cd project
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Jupyter Notebooks (in order)
data_preparation.ipynb

correlation_finding.ipynb

bitcoin_price_prediction.ipynb

## Requirements
```bash
pandas>=2.2.3  
numpy>=2.0.2  
yfinance>=0.2.54  
matplotlib>=3.8.4  
scikit-learn>=1.6.1  
transformers>=4.51.3  
torch>=2.2.2
```
# ⚠️ Disclaimer
This project is intended for educational and research purposes only. Cryptocurrency markets are highly volatile. The insights and predictions from this analysis should not be used for actual financial decisions without thorough validation and expert consultation.

