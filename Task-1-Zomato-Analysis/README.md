# Zomato Data Analysis - 

## Project Overview - 

This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** on the Zomato Bangalore dataset to uncover insights about restaurant ratings, cuisines, pricing, and location trends.

The goal is to:

* Understand factors influencing restaurant ratings
* Build a predictive model for ratings
* Provide actionable recommendations for platforms like **Alfido Tech**

---

## Dataset - 

* **Source:** Kaggle
* **Link:** https://www.kaggle.com/datasets/bhanupratapbiswas/zomato

The dataset includes:

* Restaurant name, location, cuisines
* Ratings and votes
* Cost for two people
* Online ordering & table booking availability

---

## Objectives - 

* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Identify key factors affecting ratings
* Build a machine learning model to predict ratings
* Generate business recommendations

---

## Technologies Used - 

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* WordCloud

---

## Data Cleaning & Preprocessing - 

* Removed missing and inconsistent values
* Converted ratings from text (e.g., `4.1/5`) to numeric
* Cleaned cost column (removed commas, symbols)
* Simplified cuisines (selected primary cuisine)
* Reduced high-cardinality features (top locations only)
* Converted categorical variables (Yes/No → 1/0)

---

## Exploratory Data Analysis (EDA) - 

### Key Analysis:

* Distribution of restaurant ratings
* Top cuisines and food trends
* Location-wise restaurant density
* Cost vs rating relationship
* Correlation between features

---

## Visualizations - 

* Histogram (Rating Distribution)
* Bar charts (Top Locations & Cuisines)
* Scatter Plot (Cost vs Rating)
* Heatmap (Feature Correlation)
* WordCloud (Popular Cuisines)

---

## Machine Learning Model - 

### 🔹 Model:

**Random Forest Regressor**

## Model Performance - 

* **RMSE:** ~0.30
* **R² Score:** ~0.52
  
---

## Key Insights - 

* Most restaurants have ratings between **3.5 – 4.5**
* Popular cuisines: **North Indian, Chinese, Fast Food**
* Location plays a significant role in restaurant success
* Cost has weak correlation with ratings
* Higher votes → higher credibility & ratings

---

## Business Recommendations (Alfido Tech) - 

* Promote high-rated restaurants in top locations
* Recommend trending cuisines to users
* Highlight budget-friendly top-rated options
* Partner with high-engagement restaurants
* Improve ranking using reviews & votes

---

## How to Run - 

1. Clone the repository
2. Open the notebook in Jupyter/Colab
3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
```

4. Run all cells
   
---

## Future Improvements - 

* Hyperparameter tuning for better accuracy
* Use advanced models (XGBoost, LightGBM)
* Deploy model using Streamlit/Flask
* Add sentiment analysis on reviews
* Improve feature engineering

---

## Conclusion - 

This project demonstrates a complete data science workflow:

* Data cleaning
* EDA
* Machine learning
* Business insights

The findings can help platforms like **Alfido Tech** improve recommendations, partnerships, and user experience.

---

