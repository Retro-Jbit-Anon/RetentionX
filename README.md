# RetentionX

# 📉 Customer Churn Prediction - End-to-End Machine Learning Project

This project focuses on predicting customer churn for a subscription-based business using Machine Learning. The objective is to identify customers who are likely to stop using the service, so the business can take proactive retention actions.

This is an **end-to-end data science solution** that includes:
- Data preprocessing & feature engineering
- Exploratory data analysis & visualization
- Model training, evaluation & tuning
- Model deployment (Web App API using Flask / Streamlit)
- Business insights & recommendations

---

## 📂 Project Structure
```
Customer-Churn-Prediction
│
├── data/ # Raw & cleaned datasets
├── notebooks/ # Jupyter/Colab notebooks for EDA & model building
├── src/ # Source code for model training + prediction pipeline
│ ├── data_preprocessing.py
│ ├── model_training.py
│ └── predict.py
│
├── models/ # Saved trained models (pickle / joblib)
├── webapp/ # Deployment UI (Flask or Streamlit)
│ ├── app.py
│ └── templates/ # frontend design
│
├── requirements.txt # Dependencies
└── README.md
```


---

## 🎯 Problem Statement

Customer churn directly impacts revenue growth and business stability. Identifying high-risk customers early allows companies to take corrective actions such as:
- Personalized discounts
- Loyalty benefits
- Support prioritization
- Retention campaigns

This project aims to build a model that **predicts whether a customer will churn based on historical usage and customer behavior features.**

---

## 🧠 Machine Learning Workflow

| Step | Description |
|-----|-------------|
| **1. Data Understanding** | Import dataset, interpret feature descriptions, handle missing values |
| **2. EDA** | Identify churn patterns using visualization & statistical insights |
| **3. Feature Engineering** | One-hot encoding, scaling, correlation-based selection |
| **4. Model Training** | Logistic Regression, Random Forest, XGBoost etc. |
| **5. Model Evaluation** | Accuracy, Precision, Recall, F1 Score, ROC-AUC |
| **6. Deployment** | Flask API / Streamlit Dashboard to interact with the model |

---

## 📊 Key Insights (To Fill After EDA)

- Churn rate observed = **XX%**
- Customers with **high customer service calls** showed higher churn probability.
- Lower **tenure** strongly correlates with churn.
- Monthly contract customers churn more than annual contract customers.

*(You will update these once you finish the EDA phase.)*

---

## 🧪 Model Performance (To Fill After Training)

| Model | Accuracy | Precision | Recall | F1 Score | AUC |
|------|----------|-----------|--------|---------|-----|
| Logistic Regression |  |  |  |  |  |
| Random Forest |  |  |  |  |  |
| XGBoost |  |  |  |  |  |

*(Update these after running models.)*

---

## 🚀 Deployment

The trained model is deployed as a web app using **Flask / Streamlit**.

### Run Locally:
```bash
pip install -r requirements.txt
python webapp/app.py
```
