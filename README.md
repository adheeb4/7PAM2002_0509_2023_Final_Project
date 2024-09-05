7PAM2002_0509_2023_Final_Project
Stock Market Prediction Using ML, DL, and AutoML Frameworks

This repository contains code and documentation for a comprehensive project on stock price prediction using various Machine Learning (ML), Deep Learning (DL), and Automated Machine Learning (AutoML) techniques. The objective of this project is to predict stock prices and compare the performance of different modeling approaches.

Project Overview

Stock price prediction is a crucial task in the financial industry. This project leverages multiple datasets, including historical stock prices, financial fundamentals, and sector information, to develop robust predictive models. We compare traditional ML models, advanced DL models like Long Short-Term Memory (LSTM) networks, and AutoML frameworks like H2O AutoML to determine the most effective methods for stock price forecasting.

Key Components

1. Data Preprocessing:
   - Cleaning, handling missing values, feature extraction, and scaling.
   - Merging multiple datasets to create a comprehensive feature set.

2. Feature Engineering:
   - Creation of technical indicators, rolling statistics, and financial ratios.
   - Use of time-based features such as lagged returns and moving averages.

3. Modeling Approaches:
   - Machine Learning Models: Random Forest, Gradient Boosting Machines (GBM), Support Vector Machines (SVM), etc.
   - Deep Learning Models: LSTM networks to capture temporal dependencies in stock price data.
   - Automated Machine Learning (AutoML): H2O AutoML for model selection and hyperparameter tuning.

4. Model Evaluation:
   - Evaluation using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
   - Comparative analysis of model performance.

Results

The project demonstrates that while deep learning models like LSTM effectively capture sequential patterns, AutoML frameworks provide robust and competitive performance with less manual intervention. The study also highlights the limitations posed by computational resource constraints, necessitating data downsizing and affecting model complexity.

Requirements

- Python 3.6+
- Libraries: pandas, numpy, scikit-learn, TensorFlow, Keras, H2O.ai, matplotlib, seaborn


