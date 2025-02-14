Forex Price Trend Analysis 📈

Project Overview

This project focuses on analyzing Forex price trends to gain insights into currency fluctuations and market movements. The analysis extracts data from various sources and processes it to identify key trends, patterns, and correlations in forex trading.

Problem Statement

Understanding forex market trends is crucial for making informed trading decisions. This project aims to analyze historical forex data to identify key metrics, track currency trends, and provide actionable insights for traders.

The dataset contains:

Date-wise currency exchange rates

Opening, closing, high, and low prices

Trading volume and volatility indicators

Key Insights

Trend Analysis: Identification of bullish and bearish trends over different timeframes.

Volatility Monitoring: Insights into currency pair fluctuations and market instability.

Support & Resistance Levels: Highlighting critical price levels that influence trading decisions.

Moving Averages & RSI: Calculation of technical indicators to forecast price movements.

Steps Followed

Step 1: Data Collection

Extracted forex historical price dataset from Yahoo Finance API.

Step 2: Data Preparation

Cleaned and formatted data for consistency.

Checked for missing values and removed duplicates.

Step 3: Data Processing

Applied time-series analysis to detect patterns.

Used statistical methods to calculate key financial indicators.

Step 4: Data Analysis

Computed moving averages (SMA, EMA) to smooth out price trends.

Analyzed Relative Strength Index (RSI) to determine overbought/oversold conditions.

Identified Bollinger Bands to monitor market volatility.

Implemented a Long Short-Term Memory (LSTM) model for predictive analysis.

Step 5: Model Implementation

Preprocessed data and normalized features using MinMaxScaler.

Built an LSTM model using TensorFlow/Keras with multiple layers.

Trained the model on historical forex price data to predict future price movements.

Evaluated model performance using Mean Squared Error (MSE) and visualization techniques.

Step 6: Insights & Findings

Interpreted statistical indicators to determine trading signals.

Analyzed market sentiment based on price fluctuations.

Validated LSTM model accuracy with real-time data.

Step 7: Reporting & Documentation

Summarized findings into structured documentation.

Provided recommendations based on historical trends and predictive results.

Additional Insights

Market Trends: Analyzing long-term and short-term currency fluctuations.

Trading Opportunities: Identifying potential buy/sell signals using RSI, Moving Averages, and LSTM predictions.

Risk Management: Understanding volatility and managing forex risks effectively.

Repository Contents

README.md: This file, containing an overview of the project.

Forex Price Trend Analysis.ipynb: Jupyter Notebook with data analysis, LSTM model implementation, and findings.

Datasets & Documentation: Includes CSV files and relevant documents.

How to Use

Clone the repository.

Open the .ipynb file using Jupyter Notebook.

Train and test the LSTM model with the provided dataset.

Modify the model parameters to experiment with different predictions.

🔗 Links

Dataset Source: Yahoo Finance

Project Documentation: (Include any additional documentation link)
