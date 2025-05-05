# ⚡ Forecasting Electricity Demand PJM and MISO Markets
This is a final capstone group based project that I made for the course MGT300 at the University of Toronto. The dataset used for this project comes from Kaggle and it contains 5 years of time series data split into 15-minute intervals on MISO and PJM electricity markets. 

PJM and MISO are two major U.S. regional transmission organizations (RTOs) that manage electricity flow, pricing, and reliability across multiple states. They operate wholesale electricity markets and ensure real-time balancing of supply and demand on the power grid.

## 🎯 Objectives
Firts, explore and looks for useful insights and observations

Specifically, we wants to explore the following variables:
- Seasonal electricity demand in both markets from 2019 to 2024
- Seasonal real time energy price in both markets from 2019 to 2024
- Monthly Distribution of various energy sources over the studied period
- Trend in monthly congestion costs
- Distribution of various useful variables or predictors

Second, build and fine tune a machine learning model to predict the real time energy demand in both markets. The underlying algorithm is Decision Tree machine learning model.

This model focus on solving this question:
**"Is there a statistically significant relationship between electricity prices/demand and key operational metrics of the electricity market?"**

## 📦 Dataset
- **Source**: Kaggle — U.S. Electricity Market Data by Jared Andreatta
- **Period**: 2019–2024
- **Granularity**: 15-minute intervals
- **Size**: ~44,000 rows × 46 columns
