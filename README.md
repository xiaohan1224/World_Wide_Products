## World Wide Products Inc.

## orld Wide Products time series forecasting

Resource: https://www.kaggle.com/felixzhao/productdemandforecasting

The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Time series forecasting models were applied:
      
        1. Arima
        2. Prophet 

## Purpose:
   To determine the order demand trend of certain products. 

## Main steps:
   1. Data Preparation
   2. Feature engineeirng
   4. Arima and prophet time series forecasting models are applied

## Result:
The result is not really applealing, sicne from the time series, the order demand trend for product 1278 is not decreasing, while the time series focasting result suggested that the predicted trend is decresing. 

## Project Structure

```bash

.
├── notebooks 
│     └── World_Wide_Products_Inc.ipynb
├── README.md
└── data
      └── Historical Product Demand.csv.zip
```
