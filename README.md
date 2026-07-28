# AI-Powered Stock Price Forecasting and Sentiment Analysis Dashboard for Tech Giants

## Overview

This project is an AI-powered interactive dashboard that combines Machine Learning-based stock price forecasting with sentiment analysis to analyze and visualize the performance of major technology companies.

The system uses historical stock market data, technical indicators, machine learning predictions, and news-based sentiment insights to provide users with an interactive platform for understanding stock trends.

The dashboard focuses on five major technology companies:

- Apple (AAPL)
- Microsoft (MSFT)
- Amazon (AMZN)
- Google (GOOGL)
- Meta (META)


## Key Features

### 📈 Stock Price Forecasting
- Predicts future stock prices using a Machine Learning model.
- Implements Random Forest Regression for forecasting.
- Evaluates model performance using RMSE (Root Mean Square Error).

### 📊 Technical Analysis
The project calculates important financial indicators:

- Moving Average (MA5)
- Moving Average (MA20)
- Price Change Percentage
- Volume Change
- Relative Strength Index (RSI)

### 📰 Sentiment Analysis
- Integrates stock-related news data.
- Provides sentiment-based market insights.
- Helps understand the impact of news trends on stock movement.

### 🤖 AI Project Assistant Chatbot
The dashboard includes an AI assistant that explains:
- Stock indicators
- Project workflow
- Model performance
- Dashboard usage
- User benefits

### 📌 Interactive Dashboard
Built using Streamlit with:
- Interactive charts
- Company comparison
- Prediction visualization
- Sentiment analysis graphs
- Live news headlines


## Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Random Forest Regression

### Data Processing
- Pandas
- NumPy

### Visualization
- Streamlit
- Plotly

### APIs
- Yahoo Finance API
- NewsAPI


## Project Workflow

1. Historical stock market data is collected using Yahoo Finance.
2. Data preprocessing and feature engineering are performed.
3. Technical indicators such as RSI and Moving Averages are generated.
4. Sentiment information is integrated with stock analysis.
5. Random Forest Regression model is trained.
6. Model performance is evaluated using RMSE.
7. Results are displayed through an interactive Streamlit dashboard.


## Installation and Setup

### Requirements

- Python 3.10 or above
- Internet connection
- VS Code / PyCharm / Python IDE


### Install Dependencies

Run:

```bash
pip install streamlit yfinance pandas numpy plotly scikit-learn requests
## Running the Project

1. Save the main project file as:

```text
app.py

2. Run the Streamlit application:

```bash
streamlit run app.py
3. After running the command, the dashboard will open automatically in your browser.

If it does not open automatically, open this link manually:

http://localhost:8501
## Project Structure

The project follows this structure:

AI-Stock-Price-Forecasting-Sentiment-Analysis-Dashboard

│── app.py  
│── requirements.txt  
│── README.md  
│── .gitignore  
│  
└── screenshots  
    ├── dashboard.png  
    ├── prediction.png  
    └── chatbot.png  


## Model Details

### Machine Learning Algorithm

**Random Forest Regression**

### Evaluation Metric

**RMSE (Root Mean Square Error)**

The model uses the following features for prediction:

- Historical closing price
- Moving Average (MA5)
- Moving Average (MA20)
- Price Change
- Volume Change
- Relative Strength Index (RSI)
- Sentiment Score


## Applications

This project can be used for:

- Understanding stock market trends through interactive visualization.
- Learning financial indicators and machine learning applications.
- Demonstrating an end-to-end Artificial Intelligence and Data Science workflow.
- Exploring the relationship between market data and sentiment analysis.


## Limitations

- Stock prices are affected by unpredictable market conditions.
- Predictions are not guaranteed financial advice.
- Sentiment analysis depends on available news data.
- Machine learning models may not capture every market movement.


## Future Enhancements

Possible improvements include:

- Implementing advanced NLP models such as FinBERT for financial sentiment analysis.
- Using deep learning models like LSTM for time-series forecasting.
- Deploying the dashboard on cloud platforms.
- Adding portfolio optimization and risk analysis features.


## Author

**Prerna Choudhary**

AI & Data Science Undergraduate

Skills:
Python | Machine Learning | Artificial Intelligence | Data Analytics