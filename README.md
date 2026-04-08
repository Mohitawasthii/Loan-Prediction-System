# 🏦 Loan Approval Prediction System

🚀 **End-to-End Machine Learning Project | Production-Ready | Deployable API**

---

## 📌 Overview

This project builds a **Loan Approval Prediction System** using Machine Learning to automate loan approval decisions based on applicant data.

It covers the complete ML lifecycle:
✔ Data Cleaning
✔ Exploratory Data Analysis (EDA)
✔ Feature Engineering
✔ Model Training & Evaluation
✔ Deployment (API Ready)

---

## 🎯 Problem Statement

Financial institutions receive thousands of loan applications.
Manual processing is slow, error-prone, and inefficient.

👉 This system predicts whether a loan should be approved or rejected using historical data.

---

## 📊 Dataset Features

| Feature           | Description            |
| ----------------- | ---------------------- |
| Gender            | Applicant gender       |
| Married           | Marital status         |
| Education         | Education level        |
| ApplicantIncome   | Income of applicant    |
| CoapplicantIncome | Income of co-applicant |
| LoanAmount        | Loan amount            |
| Loan_Amount_Term  | Loan duration          |
| Credit_History    | Credit score/history   |
| Property_Area     | Urban/Semi-Urban/Rural |
| Loan_Status       | Target variable        |

---

## ⚙️ Tech Stack

* 🐍 Python
* 📊 Pandas, NumPy
* 📈 Matplotlib, Seaborn
* 🤖 Scikit-learn, XGBoost
* 🌐 Flask (Deployment)
* 💾 Joblib (Model Saving)

---

## 🔍 Exploratory Data Analysis

* Checked missing values
* Visualized distributions
* Correlation analysis
* Class imbalance detection

---

## 🧹 Data Preprocessing

* Handled missing values (Mean/Median/Mode)
* Label Encoding for categorical variables
* Feature scaling using StandardScaler

---

## 🤖 Models Used

| Model               | Purpose                    |
| ------------------- | -------------------------- |
| Logistic Regression | Baseline                   |
| Random Forest       | Robust performance         |
| XGBoost             | High accuracy (Best Model) |

---

## 🏆 Model Performance

* Accuracy: **~80–90%** (depending on tuning)
* Evaluated using:

  * Confusion Matrix
  * Precision / Recall / F1-score

---

## 📁 Project Structure

```
loan-prediction/
│── data/
│   └── Loan_Train.csv
│
│── notebooks/
│   └── EDA_and_Model.ipynb
│
│── models/
│   ├── loan_model.pkl
│   └── scaler.pkl
│
│── app.py
│── requirements.txt
│── README.md
```

---

## 🚀 How to Run

### 🔹 1. Clone Repository

```bash
git clone https://github.com/yourusername/loan-prediction.git
cd loan-prediction
```

### 🔹 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 🔹 3. Run Model Training

```bash
python train.py
```

### 🔹 4. Run API

```bash
python app.py
```

---

## 🌐 API Endpoint

**POST /predict**

### Request:

```json
{
  "features": [values...]
}
```

### Response:

```json
{
  "prediction": 1
}
```

---

## 📈 Future Improvements

* Hyperparameter tuning (GridSearchCV / Optuna)
* Feature engineering (Total Income, EMI ratio)
* Handling imbalance using SMOTE
* Deploy on AWS / Azure
* Build Streamlit Web UI

---

## 🧠 Key Learnings

* End-to-end ML pipeline design
* Handling real-world missing data
* Model comparison & evaluation
* Deployment readiness

---

## 👨‍💻 Author

**Mohit Awasthi**
💼 Aspiring Data Scientist | ML Engineer

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork!

---
