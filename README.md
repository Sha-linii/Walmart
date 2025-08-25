# Walmart
Deploy predictive models to strengthen Walmart’s future planning and customer strategies.

# 🛒 E-commerce Data Analysis & Customer Insights

## 📌 Project Overview

This project explores an e-commerce dataset to deliver key business insights including:

- Sales Forecasting using Prophet
- Customer Growth Prediction
- RFM-based Customer Segmentation
- Product Return Prediction using Machine Learning

---

## 🧾 Datasets Used

- **orders**: Customer orders, timestamps
- **order_items**: Item-level sales data
- **products**: Product category metadata
- **customers**
- **sellers**
  
---

## 🛠️ Tech Stack

- Python (Pandas, Matplotlib, Seaborn)
- Prophet (Facebook)
- Scikit-learn (RandomForest, KMeans)
- Jupyter Notebook

---

## 🔹 Data Cleaning Steps
- **Datetime Conversion:** Converted date columns into datetime format for proper time series analysis.
- **Merging Datasets:** Combined orders and order_items using order_id to build a unified sales dataset.
- **Handling Missing Values:** Used fillna() to handle missing delivery_time and other key fields.
- **Data Type Fixes:** Applied transformations such as .astype(), .dt.to_period() and .dt.to_timestamp() where needed for time series and categorical processing.


## 📈 Sales Forecasting

- Monthly sales aggregated
- Prophet model used to forecast next 6 months
- Seasonal trends visualized

---

## 👥 New Customer Forecasting

- Monthly new customers tracked
- Future growth predicted with Prophet

---

## 🧮 RFM Customer Segmentation

- Metrics: Recency, Frequency, Monetary
- Clustering using KMeans
- Segments:
  - **Loyal High-Value Customers**
  - **Potential Loyalists**
  - **Discount Seekers**
  - **Churn Risk**

---

## 🔁 Return Prediction

- Features: price, delivery time, freight, category
- Model: RandomForestClassifier
- Evaluation: Confusion matrix, feature importance

---

## 📌 Key Learnings

- Time series forecasting reveals seasonality in sales and customer trends  
- RFM segmentation supports targeted marketing strategies  
- Delivery time and product pricing are key return drivers

---

## 🚀 Next Steps

- Integrate customer reviews & ratings
- Enable real-time dashboards (e.g., with Streamlit)
- Explore neural networks for advanced forecasting
