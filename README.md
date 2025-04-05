# 🚀 BDA_Project_24-25

## 📖 Overview

This project is part of the **Big Data Analytics (BDA) course** in the **Master's in Data Science and Advanced Analytics** at **NOVA IMS**.  
It focuses on solving a **real-world Big Data problem** by leveraging **Apache Spark, Machine Learning, and Data Visualization** techniques.

📅 **Project Deadline**: May 25, 2025  

👥 **Contributors | Group 12**:  
- Diogo Rodrigues, 20240512  
- Rafael Silva, 20240511  
- Zofia Wójcik, 20240654  

---

## 🎯 **Project Objective**

> _Can we predict the box office revenue of a movie before it is released?_  
This project explores that question by building a **machine learning regression model** using **Apache Spark MLlib** to predict the **revenue** of a movie based on features such as budget, genre, popularity, vote average, and more.

Accurate revenue predictions are valuable for studios, investors, and distributors, offering insights into risk management, marketing strategies, and production planning.

---

## 📊 **Dataset**

- **Data Source**: [Full IMDb Movies Data on Kaggle](https://www.kaggle.com/datasets/anandshaw2001/imdb-data)  
- **Format**: CSV (~50,000 movie records)  
- **Preprocessing Steps**:
  - Handling missing values in budget and revenue
  - One-hot encoding of categorical variables (e.g., genres, original language)
  - Feature extraction from text columns (overview, keywords)
  - Normalization and log-scaling for skewed numerical features

---

## 🛠 **Technology Stack**

| Component            | Technology Used             |
|---------------------|-----------------------------|
| **Data Ingestion**   | CSV loading in Databricks   |
| **Processing**       | Apache Spark (SQL, MLlib)   |
| **Storage**          | Databricks File System (DBFS) |
| **Machine Learning** | Spark MLlib – Linear Regression, Random Forest |
| **Visualization**    | Databricks Visualizations, Matplotlib |
| **Deployment**       | (Optional – Not deployed)   |

---

## 🏗 **Methodology**

1. **Problem Definition**: Frame revenue prediction as a supervised regression task.
2. **Data Collection**: Load dataset from Kaggle via Databricks notebook.
3. **Preprocessing**: Clean and engineer features (budget, genres, language, popularity).
4. **Big Data Processing**: Use Apache Spark to scale processing to large datasets.
5. **Machine Learning**: Train regression models (Linear Regression, Decision Trees).
6. **Evaluation**: Use RMSE, MAE, and R² for performance assessment.
7. **Visualization**: Analyze feature importance and actual vs. predicted revenue plots.

---

## 📈 **Results & Insights**

> _Final results and visual insights will be updated upon project completion._  
So far, we expect:
- ✅ Identification of the most predictive features for revenue (e.g., budget, popularity)
- ✅ Regression model with explainable performance metrics
- ✅ Clear business insights for production and marketing strategies

---

## 🛠 **Installation & Setup**

To run this project locally (if not using Databricks), follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/merkury00/BDA_Project_24-25.git
cd BDA_Project_24-25
