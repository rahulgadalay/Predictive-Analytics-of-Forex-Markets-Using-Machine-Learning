# 📈 Forex Market Prediction Using Machine Learning

> A Machine Learning-based predictive analytics system for forecasting Forex market trends using historical exchange rate data and technical indicators.

---

## Overview

This project focuses on forecasting foreign exchange (Forex) market trends using Machine Learning and Predictive Analytics techniques. Historical exchange rate data is preprocessed and transformed through feature engineering before being used to train predictive models.

The project evaluates multiple forecasting approaches using statistical performance metrics and compares their prediction accuracy across different forecasting horizons.

The research work is associated with an IEEE conference publication on Forex Market Predictive Analytics.

---

## Objectives

- Forecast future Forex exchange rates
- Perform feature engineering on historical market data
- Compare multiple machine learning models
- Evaluate prediction accuracy using MSE
- Visualize forecasting performance

---

## Dataset

The project uses historical exchange rate datasets for:

- EUR/USD
- GBP/USD

The datasets include market attributes such as:

- Open
- High
- Low
- Close
- Volume
- Percentage Change

---

## Feature Engineering

Several technical indicators are generated to improve prediction performance.

- Simple Moving Average (SMA)
- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)
- True Range
- Maximum Range
- Minimum Range
- Percentage Change

---

## Machine Learning Pipeline

Historical Dataset

↓

Data Cleaning

↓

Feature Engineering

↓

Feature Scaling

↓

Model Training

↓

Prediction

↓

Performance Evaluation

↓

Visualization

---

## Models Used

- Extreme Learning Machine (ELM)
- Back Propagation Neural Network (BPNN)
- Functional Link Artificial Neural Network (FLANN)

---

## Performance Metrics

The models are evaluated using:

- Mean Squared Error (MSE)

Prediction horizons:

- 1 Day
- 3 Days
- 5 Days
- 7 Days

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Machine Learning
- Predictive Analytics

---

## Repository Structure

```
Forex-Market-Prediction-Using-Machine-Learning/
│
├── notebooks/
├── data/
├── docs/
├── images/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Future Improvements

- Deep Learning (LSTM)
- Transformer Models
- Real-time Forex prediction
- Deployment using Streamlit
- Live market data integration

---

## Author

**Rahul Gadalay**

Software Engineer | Data Engineering | Machine Learning | Generative AI
