# 📊 Churn Analysis Project

## 📌 Overview
Churn Analysis is the process of identifying customers who are likely to stop using a service. This project aims to predict customer churn using **machine learning models** and **data analysis techniques**.

## 📂 Project Structure
```
Churn_analysis/
│── data/                # Dataset files
│── notebooks/           # Jupyter Notebooks for analysis & model training
│── src/                 # Source code for preprocessing and modeling
│── models/              # Saved trained models
│── powerbi/             # Power BI visualizations and reports
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```

## 📊 Dataset Description
The dataset used for this analysis contains customer attributes such as:

| **Attribute**                  | **Description** |
|--------------------------------|---------------|
| **Customer_ID**               | Unique identifier for each customer. |
| **Gender**                    | Gender of the customer (Male/Female). |
| **Age**                        | Age of the customer. |
| **Married**                    | Whether the customer is married (Yes/No). |
| **State**                      | The state where the customer resides. |
| **Number_of_Referrals**        | Number of referrals made by the customer. |
| **Tenure_in_Months**           | Total number of months the customer has been with the company. |
| **Value_Deal**                 | Whether the customer is on a value deal (Yes/No). |
| **Phone_Service**              | Whether the customer has phone service (Yes/No). |
| **Multiple_Lines**             | Whether the customer has multiple phone lines (Yes/No). |
| **Internet_Service**           | Whether the customer has internet service (Yes/No). |
| **Internet_Type**              | Type of internet connection (Fiber, DSL, etc.). |
| **Online_Security**            | Whether the customer has online security services (Yes/No). |
| **Online_Backup**              | Whether the customer has an online backup plan (Yes/No). |
| **Device_Protection_Plan**     | Whether the customer has device protection (Yes/No). |
| **Premium_Support**            | Whether the customer has premium customer support (Yes/No). |
| **Streaming_TV**               | Whether the customer subscribes to streaming TV services (Yes/No). |
| **Streaming_Movies**           | Whether the customer subscribes to streaming movie services (Yes/No). |
| **Streaming_Music**            | Whether the customer subscribes to streaming music services (Yes/No). |
| **Unlimited_Data**             | Whether the customer has an unlimited data plan (Yes/No). |
| **Contract**                   | Type of contract (Month-to-Month, One-Year, Two-Year). |
| **Paperless_Billing**          | Whether the customer uses paperless billing (Yes/No). |
| **Payment_Method**             | Customer's preferred payment method (Credit Card, Bank Transfer, etc.). |
| **Monthly_Charge**             | The amount the customer is charged per month. |
| **Total_Charges**              | Total charges incurred by the customer during their tenure. |
| **Total_Refunds**              | Total amount refunded to the customer. |
| **Total_Extra_Data_Charges**   | Additional charges due to extra data usage. |
| **Total_Long_Distance_Charges** | Charges for long-distance calls. |
| **Total_Revenue**              | Total revenue generated from the customer. |
| **Customer_Status**            | Whether the customer is Active, Inactive, or Churned. |
| **Churn_Category**             | The category of churn (Voluntary, Involuntary, etc.). |
| **Churn_Reason**               | Specific reason why the customer churned. |


## 🚀 Technologies Used
- **Python** 🐍
- **Pandas, NumPy** 📊 (Data Processing)
- **Matplotlib, Seaborn** 📈 (Data Visualization)
- **Scikit-learn** 🤖 (Machine Learning Models)
- **Power BI** 📊 (Data Visualization and Reporting)

## 🏗️ Installation & Setup
To run this project locally, follow these steps:

1️⃣ **Clone the repository**:
```sh
 git clone https://github.com/Dineshchowdaryjampala/Churn_analysis.git
 cd Churn_analysis
```

2️⃣ **Install dependencies**:
```sh
 pip install -r requirements.txt
```

3️⃣ **Run Jupyter Notebook**:
```sh
 jupyter notebook
```

## 📉 Data Analysis & Visualization
![Churn Distribution](https://github.com/Dineshchowdaryjampala/Churn_analysis./blob/ac74da0bf8a97f936cae3a869e0f5ed928ac40f7/Images/Dashboard%20of%20Summary%20Data.png)

- Analyzed churn distribution across various demographics.
- Visualized trends in customer behavior leading to churn.
- **Used Power BI** to explore raw data, creating interactive dashboards for better insights.

## 🤖 Machine Learning Models
The project implements multiple machine learning models to predict churn:
1. **Logistic Regression**
2. **Random Forest**(choosed for **POWER BI** visualization)
3. **XGBoost** 
4. **Neural Networks** *(Optional)*

### 📊 Model Performance
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | 85% | 82% | 78% | 80% |
| Random Forest | 84% | 78% | 80% | 84% |

## 📜 Key Findings
- Customers with **higher monthly charges** are more likely to churn.
- **Long-term contracts** reduce churn significantly.
- **Good customer service** helps retain users.

## 📊 Power BI for Data Visualization
1. **Raw Data Exploration**: Used Power BI to visualize initial dataset trends and correlations.
2. **Post-Modeling Analysis**: After performing the **Random Forest Algorithm**, the obtained dataset was further visualized using **Power BI**.
3. **Final Dashboard**: Created **interactive reports** to track churn patterns and model predictions.

![Power BI Dashboard](https://github.com/Dineshchowdaryjampala/Churn_analysis./blob/ca80762b7259ffee230fd6744fb84c1d3534ce7f/Images/Summary%20of%20Predicted%20Data.png)

## 📌 Future Improvements
- **Hyperparameter tuning** for better model performance.
- **Deep Learning models** for improved predictions.
- **Real-time prediction API** using Flask or FastAPI.
- **Enhanced Power BI dashboards** with predictive analytics integration.

## 📢 Contributing
Feel free to **fork** this repository, create a **new branch**, and submit a **pull request**!

## 📬 Contact
📧 Email: dineshwalker143@gmail.com
🔗 GitHub: [Your Profile](https://github.com/Dineshchowdaryjampala)

🚀 **Star this repository** if you find it useful! Happy Coding! 😊
