# marketanomalies
Project Overview
This project explores how to identify outliers and market anomalies using the Volatility Index (VIX) and the S&P 500. It also tracks market sentiment and applies it to specific stocks. The analysis involves data extraction, feature creation, and applying machine learning techniques to detect anomalies and patterns in the market.

Key Features
Data Collection: Fetches data from Yahoo Finance for VIX and S&P 500.
Data Cleaning and Preparation: Checks for missing values, converts data types, and creates new features such as high-low and open-close price changes, Relative Strength Index (RSI), Detrended Price Oscillator (DPO), and Pring Special K indicator.
Feature Engineering: Combines different data sources into a single dataframe, preparing it for analysis and visualization.
Anomaly Detection: Uses Isolation Forest, a machine learning algorithm, to detect outliers in the dataset.
Visualization: Utilizes Plotly and Matplotlib to create interactive and static plots for data exploration and analysis.
