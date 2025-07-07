# 📊 Customer Churn Prediction System

This project predicts whether a customer is likely to churn using machine learning classification models. It helps businesses proactively retain customers by identifying key churn drivers and high-risk users. The system includes end-to-end steps from data cleaning to model deployment and visualization using Power BI.


## 🚀 Project Objective

To build a machine learning model that predicts customer churn probability, identify key factors influencing churn, and present actionable business insights through a dashboard.

## 🧰 Tools & Technologies Used

- **Python** (Google Colab)
- **Pandas, Scikit-learn** – Data cleaning, preprocessing, model training
- **XGBoost, Random Forest, Logistic Regression** – ML algorithms
- **Matplotlib, Seaborn** – Data visualization
- **Power BI** – Final dashboard presentation
- **Streamlit** (optional attempt)


## 🗂️ Dataset Used

- Source: Kaggle - [Telco / Bank / Spotify Customer Churn Dataset]
- Rows: 7032  
- Target: `Churn` (Yes/No)

## 🛠️ Project Workflow

1. **Exploratory Data Analysis**
2. **Data Cleaning & Preprocessing**
   - Removed nulls
   - Encoded categorical variables
   - Feature selection
3. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix
5. **Churn Probability Prediction**
6. **Feature Importance Analysis**
7. **Top 10 High-Risk Customer Extraction**
8. **Power BI Dashboard & Business Insights**

---

## 📈 Model Evaluation Summary

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 86%      | 82%       | 79%    | 80%      |
| Random Forest      | 89%      | 84%       | 83%    | 83%      |
| XGBoost            | 90%      | 86%       | 84%    | 85%      |

> ✅ **Best Performing Model: XGBoost**

## 📊 Key Visualizations (Power BI)

- 🔹 Bar Chart: Feature Importance (Top 10 Churn Drivers)
- 🔹 Pie Chart: Churned vs Retained Customers
- 🔹 Column Chart: Churn by Contract Type
- 🔹 Table: Top 10 High-Risk Customers
- 🔹 KPI Cards: Total Customers, Avg Tenure, Churn Rate

## 📤 Output Files

| File                      | Description                            |
|---------------------------|----------------------------------------|
| `final_df.csv`            | Cleaned and encoded dataset            |
| `feature_importance.csv`  | Top churn-driving features             |
| `top_risk_customers.csv`  | Customers with highest churn probability |
| `customer_churn.pbix`     | Power BI dashboard                     |

---

## 💼 Business Recommendations

- Customers with **monthly contracts** are more likely to churn
- High **MonthlyCharges** increase churn risk
- **Tenure** is negatively correlated with churn
- **Electronic checks** indicate higher churn
- Offer **loyalty rewards** and improve onboarding for at-risk segments

## 📌 Optional Deployment

> Streamlit version of this model was attempted but is not deployed due to ngrok compatibility. Future improvement can integrate full web UI.

## 📁 How to Run

### ▶️ In Google Colab
1. Upload dataset
2. Run cells in order from top to bottom
3. Download output CSVs for Power BI

### ▶️ In Power BI
1. Import the `.csv` files as data sources
2. Create visuals using recommended charts
3. Save as `.pbix` or export to PDF

✅ Author

Advaita_S_S

BSc Computer Science (Data Analytics) Student

Machine Learning Intern @ Future Interns
📅 July 2025

> 📌 This project is an independently developed academic work.




