# Bank_Customer_Churn_Model
This project predicts whether a bank customer will churn (exit) or not, using machine learning models.

[Open Notebook in Colab](https://colab.research.google.com/github/dhankarsimran/Bank_Customer_Churn_Model/blob/main/Bank_Customer_Churn_Model.ipynb)

## 📌 Project Overview

Customer churn is one of the biggest challenges for banks and financial institutions. This project predicts whether a bank customer is likely to leave (churn) based on their demographic and account details.

The goal is to build machine learning models that help banks identify customers at risk of leaving, so they can take proactive retention steps.

### 🚀 Key Features

✅ Data preprocessing (handling categorical & numerical variables)

✅ Exploratory Data Analysis (EDA) with visual insights

✅ Machine Learning Models:

#### Logistic Regression

#### Gradient Boosting Classifier

✅ Model Evaluation using Accuracy, Precision, Recall, F1 Score, ROC-AUC

✅ Conclusion on best-performing model

### 📊 Results

| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| ------------------- | -------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 80.8%    | 0.59      | 0.18   | 0.72     | 0.77    |
| Gradient Boosting   | 88.7%    | 0.76      | 0.49   | 0.86     | 0.88    |

👉 Gradient Boosting outperforms Logistic Regression with higher recall, precision, and overall AUC, making it the preferred model for churn prediction.

📂 **Project Structure**

```Bank_Customer_Churn_Model/
│
├── Bank_Customer_Churn_Model.ipynb   # Jupyter Notebook with code
├── data/                             # Dataset (https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling?resource=download)
└── README.md                         # Project documentation
```

 ### 📑 Dataset [Link](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling?resource=download)

The dataset includes information such as:

Customer demographics (age, gender, geography)

Account information (balance, credit score, estimated salary)

Banking behavior (active membership, number of products, tenure)

###### 📌 Target Variable: Exited (1 → customer churned, 0 → customer stayed).

### ⚙️ Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Google Colab / Jupyter Notebook

### 📈 Results Visualization

ROC Curve Comparison

Confusion Matrix

Feature Importance from Gradient Boosting

### 📈 Insights

Age, balance, and tenure significantly influence churn.

Logistic Regression provides baseline performance.

Gradient Boosting is more effective in identifying customers likely to leave.

#### ✨ If you like this project, feel free to star ⭐ the repo and connect with me!
