# 🌍 Global Temperature Analysis with PySpark & Databricks

This project was developed as a final assignment for the **Big Data Analytics** course at ITBA.  
We used **Apache Spark on Databricks Community Edition** to explore and model global climate data at scale — focusing on trends in temperature variation in India.

---

## 🚀 Project Overview

The goal was to apply Spark to a large-scale dataset from the **Berkeley Earth Surface Temperature Study**, which includes over 1.6 million global records from 1743 to 2013.  
Using Databricks Community allowed us to process, clean, and analyze this data **efficiently despite platform limitations** — demonstrating Spark’s scalability even in free environments.

---

## 🔍 What We Did

- **Data ingestion** from `.csv` files using Spark’s file system interface  
- **Cleaning & enrichment**: date parsing, coordinate correction, missing values, data types  
- **EDA**: filtering by country, variable distributions, boxplots, histograms, and outlier detection  
- **Time series decomposition** of temperature into trend/seasonality using Spark window functions  
- **Modeling** with:
  - **ARIMA**
  - **Prophet**
  - **Random Forest Regressor** (best performance, selected model)

---

## 📊 Results & Insights

- **India** had the largest number of temperature records globally.
- We observed **stationary trends** in key cities but a **national upward trend in average temperature** over time.
- **Random Forest** outperformed other models in terms of prediction accuracy for short-term temperature trends.
- Full visualization of **residuals, error distributions**, and **model comparison** included.

---

## 💡 Why It Matters

This project showcases how **Spark can be applied to real-world, high-volume datasets** for climate monitoring and forecasting — and how even with limited resources (like Databricks CE), powerful analyses are possible with clean pipelines and well-chosen models.

---

## 🛠️ Stack

- **PySpark** (SQL, DataFrames, MLlib)
- **Databricks Community Edition**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Statsmodels**, **Prophet**, **scikit-learn**

---

## 📁 Files

- `spark_final_project.pdf`: Full report with code, visualizations, and conclusions (in Spanish)  
- [`Databricks Notebook`](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4500188357524398/1335014764210438/7065241058599388/latest.html): The original notebook used for this project, executed on Databricks Community Edition

> 📌 *Note: The full report is written in Spanish. A summary in English is provided above.*

---
