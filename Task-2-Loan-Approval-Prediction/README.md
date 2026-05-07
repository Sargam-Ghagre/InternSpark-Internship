# Loan Approval Prediction - 

## Project Overview - 

This project performs **data preprocessing, class imbalance handling, and supervised machine learning modeling** on the Loan Approval dataset to predict whether a loan application will be approved or not.

The goal is to:

* Predict loan approval status using borrower information
* Compare machine learning classification models
* Handle imbalanced data using SMOTE
* Provide business-oriented insights for financial institutions

---

## Dataset - 

* **Source:** Kaggle
* **Link:** https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study

The dataset includes:

* Applicant income and coapplicant income
* Loan amount and loan term
* Credit history
* Education and employment details
* Property area and marital status
* Loan approval status

---

## Objectives - 

* Perform data cleaning and preprocessing
* Handle missing values and categorical encoding
* Scale numerical features
* Handle class imbalance using SMOTE
* Compare machine learning classification models
* Evaluate models using Precision, Recall, F1-score and ROC-AUC
* Generate business recommendations for loan approval systems

---

## Technologies Used - 

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## Data Cleaning & Preprocessing - 

* Removed unnecessary columns (`Loan_ID`)
* Handled missing values using median and mode imputation
* Encoded categorical variables using OneHotEncoder
* Standardized numerical features using StandardScaler
* Created preprocessing pipeline using ColumnTransformer

---

## Handling Class Imbalance - 

The dataset contained imbalanced target classes.

To improve minority class prediction:

* Applied **SMOTE (Synthetic Minority Oversampling Technique)**
* Balanced the training dataset before model training

---

## Exploratory Data Analysis (EDA) - 

### Key Analysis:

* Loan approval distribution
* Credit history impact on loan approval
* Income distribution of applicants
* Relationship between loan amount and approval
* Correlation between numerical features

---

## Visualizations - 

* Count Plot (Loan Approval Distribution)
* Histogram (Applicant Income Distribution)
* Correlation Heatmap
* ROC-AUC Comparison Chart
* Confusion Matrix

---

## Machine Learning Models - 

### Models Used:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

## Model Evaluation Metrics - 

The models were evaluated using:

* Precision
* Recall
* F1-score
* Accuracy
* ROC-AUC Score

---

## Best Model - 

### Logistic Regression

Logistic Regression was selected as the preferred deployment model because:

* It provided strong ROC-AUC performance
* It is highly interpretable
* It is suitable for financial decision-making systems
* It performs reliably on small structured datasets

---

## Key Insights - 

* Applicants with strong credit history are more likely to receive loan approval
* Higher applicant income improves approval probability
* Lower loan amount reduces lending risk
* Balanced debt-to-income ratio positively impacts approval chances
* SMOTE improved minority class prediction performance

---

## Business Recommendations - 

* Use machine learning models for preliminary loan screening
* Increase approval threshold from 0.50 to 0.60 to reduce risky approvals
* Prioritize applicants with strong credit history
* Use predictive analytics to minimize loan default probability
* Improve loan decision consistency using automated systems

---

## How to Run - 

1. Clone the repository
2. Open the notebook in Jupyter Notebook or Google Colab
3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

4. Run all notebook cell

---

   
## Future Improvements -
* Perform hyperparameter tuning
* Use advanced boosting models (XGBoost, LightGBM)
* Deploy model using Streamlit or Flask
* Add explainable AI techniques (SHAP, LIME)
* Integrate real-time loan application systems

---

## Conclusion -

This project demonstrates a complete machine learning workflow for loan approval prediction:

* Data preprocessing
* Feature engineering
* Class imbalance handling
* Model comparison
* Performance evaluation
* Business interpretation

The solution can help financial institutions improve loan approval efficiency, reduce default risk, and support data-driven lending decisions.

---
