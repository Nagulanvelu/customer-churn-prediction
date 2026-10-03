# 📊 Customer Churn Prediction | Machine Learning

A machine learning project that predicts whether a telecom customer is likely to churn.

## 🎯 Project Overview

Customer churn is an important business problem where customers stop using a company's services.

This project uses the **Telco Customer Churn** dataset to explore customer behavior and build machine learning models for churn prediction.

## 🔬 Workflow

**Data Collection → Data Cleaning → Exploratory Data Analysis → Feature Engineering → Model Training → Model Evaluation → Feature Analysis**

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Models

- Logistic Regression
- Random Forest Classifier

## 📈 Model Results

| Model | Accuracy | Churn Recall | Churn F1-Score |
|---|---:|---:|---:|
| Logistic Regression | 80.38% | 57.49% | 60.91% |
| Random Forest | 79.03% | 50.27% | 56.04% |

## 🔍 Key Findings

- Churn was more concentrated among month-to-month customers.
- Customers with shorter tenure showed more churn cases in this dataset.
- `TotalCharges`, `tenure`, and `MonthlyCharges` had relatively high feature importance in the Random Forest model.
- The analysis describes patterns in the dataset and does not establish causal relationships.

## 📂 Dataset

**Telco Customer Churn Dataset** by BlastChar.

The cleaned dataset contains **7,032 customer records and 21 columns**.

## 🔗 Project Notebook

👉 [View the complete Kaggle Notebook](https://www.kaggle.com/code/nagulannagul/customer-chrun-prediction-machine-learning)

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost and boosting models
- Class-imbalance techniques
- Probability threshold optimization
- SHAP-based model explainability
- Streamlit deployment

## 👨‍💻 Author

**Nagulan V**

AI Student | Python | Data Science | Machine Learning
