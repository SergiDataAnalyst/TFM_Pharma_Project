# TFM_Pharma_Project 💊 

# Pharma Sales Recommendation System

This project leverages machine learning to support pharmaceutical sales teams by recommending the most suitable products to promote during their next visit to healthcare professionals. By analyzing historical sales data, client preferences, and other relevant variables, the system provides smart product recommendations to maximize sales efficiency and effectiveness.

## Project Goals

- Predict the most relevant products for each sales representative to recommend.
- Improve targeting and personalization of sales visits.
- Optimize product promotions based on historical data and customer behavior.

## Technologies & Tools

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)
- **Jupyter Notebooks** for experimentation and prototyping
- **MLflow** or similar for tracking experiments
- **Streamlit** 
- **GitHub** for version control

## Data Sources

*Note: We will be using anonymized data for public repositories.*

- Sales logs (salesperson, product, customer, date)
- Customer profiles (specialty, location, past interactions)
- Product metadata (category, usage, launch date)
- Visit history and outcomes

## Features

- Data preprocessing & feature engineering
- Multiple ML models tested (Random Forest, XGBoost, etc.)
- Evaluation metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC)
- Top-N product recommendation logic
- Dashboard to visualize and explore predictions

## How It Works

1. **Ingest & clean** historical sales data.
2. **Engineer features** to capture temporal trends, preferences, and interaction history.
3. **Train models** to classify or rank products per customer per visit.
4. **Generate recommendations** for each salesperson.
5. **Deploy** as a web app or API for real-time usage.

## Example Use Case

> On the eve of a scheduled visit, a sales rep logs in and sees the top 3 product recommendations to pitch based on that doctor’s profile, preferences, and market trends.


