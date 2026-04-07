# Loan-Prediction-System
End-to-end Loan Prediction System using Python (Pandas, Scikit-learn) covering EDA, pre-processing, model training, evaluation, and deployment with real-world dataset.
# 🏦 Loan Prediction System (End-to-End Data Science Project)

## 📌 Project Overview

This project builds a complete **Machine Learning pipeline** to predict whether a loan will be approved or not based on applicant details.

It covers the full lifecycle of a Data Science project:

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Preprocessing
* 🤖 Model Training & Selection
* 📈 Performance Evaluation
* 🚀 Model Deployment

---

## 📂 Dataset

* **File:** `Loan_Train.csv`
* Contains applicant information such as:

  * Gender
  * Marital Status
  * Income
  * Loan Amount
  * Credit History
  * Loan Status (Target)

---

## ⚙️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib & Seaborn
  * Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked missing values
* Visualized target distribution
* Correlation heatmap
* Feature relationships

---

## 🧹 Data Preprocessing

* Handled missing values using:

  * Median (numerical features)
  * Mode (categorical features)
* Encoded categorical variables using Label Encoding
* Feature Scaling using StandardScaler

---

## 🤖 Model Training

Multiple models were trained:

* Logistic Regression
* Decision Tree
* Random Forest ⭐ (Best Model)

---

## 📈 Model Performance

* Evaluated using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

👉 **Best Model:** Random Forest Classifier

---

## 🚀 Deployment

The trained model is saved using **Pickle**:

```bash
loan_model.pkl
scaler.pkl
```

You can load and use it for predictions:

```python
import pickle

model = pickle.load(open("loan_model.pkl", "rb"))
scaler = pickle.load(open("scaler.pkl", "rb"))
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/loan-prediction.git
cd loan-prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Script

```bash
python main.py
```

---

## 📁 Project Structure

```
├── Loan_Train.csv
├── main.py
├── loan_model.pkl
├── scaler.pkl
├── README.md
└── requirements.txt
```

---

## 💡 Key Learnings

* Handling missing data effectively
* Importance of feature scaling
* Model comparison and selection
* End-to-end ML pipeline development

---

## 📌 Future Improvements

* Hyperparameter tuning
* Use advanced models (XGBoost, LightGBM)
* Build a web app using Flask/Streamlit

---

## 🙌 Author

**Mohit Awasthi**
📧 Connect with me for collaboration

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
