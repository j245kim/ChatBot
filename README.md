# STFO: Cryptocurrency Robo-Advisor

## Overview
This project involves developing a chatbot that generates market analysis reports based on real-time cryptocurrency market data and news articles. The goal is to assist users in making informed decisions in the highly volatile cryptocurrency market.
This is a translated version of code that is written in Korean!

## Original file
https://github.com/j245kim/STFO

## Collaborator
https://github.com/ChoJunHee-user
https://github.com/privatepeople
https://github.com/happy-dragonman

## Key Features

### 1. Data Collection
- Utilize `pyupbit` to gather cryptocurrency data such as prices, trading volume, and volatility.
- Employ web crawling to collect news data from reliable sources such as Investing.com and Korea Economic Daily.

### 2. Data Analysis
- **Mean Analysis**: Perform T-tests to analyze relationships between major cryptocurrencies.
- **Correlation Analysis**: Examine Pearson correlation coefficients between key cryptocurrencies.
- **Dynamic Time Warping (DTW)**: Measure similarities in price movements of cryptocurrencies.
- **Liquidity Breakout Strategy**: Detect potential price changes triggered by surges in trading volume.

### 3. Chatbot
- Build a chatbot using **Streamlit** and **LangChain** to answer users’ questions about the market.
- Implement data storage and retrieval using **FAISS** for fast and context-aware responses.
- Automatically generate analysis reports based on user queries.

## Core Technologies
- **Python**: Libraries such as `pyupbit`, `LangChain`, `seaborn`, `matplotlib`, and `FAISS`.
- **Chatbot Platform**: Streamlit and LangChain.
- **Data Sources**: Market data and news from Investing.com, Korea Economic Daily, and other trusted platforms.

## How to Run

### 1. Install Required Libraries
Install the required libraries to meet the project's dependencies:
```bash
pip install -r requirements.txt

cd <project_directory>
streamlit run app.py
