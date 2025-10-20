# 🪙 Silver Price Forecasting using Statistical and Adaptive Models

This project forecasts **next-day silver prices** using a combination of time series techniques, adaptive weighting, and ensemble forecasting methods.  
It compares simple yet powerful approaches such as **Exponential Smoothing**, **Adaptive Weighted Average**, **Momentum-Based Forecasting**, and **Naive Models**, then combines them for a more stable and robust prediction.

---

## 📈 Overview

The model retrieves **daily silver futures data (`SI=F`)** from Yahoo Finance (via `yfinance`) and analyzes price movement trends from **2020 to present**.

The goal is to:
- Analyze recent volatility in silver prices  
- Compare forecasting models based on **Mean Absolute Error (MAE)**  
- Generate a **final ensemble prediction** using a trimmed mean of all methods  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/silver-price-forecast.git
cd silver-price-forecast
