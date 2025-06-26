# loan-default-prediction-risk-engine
ML model to predict loan default with SHAP explainability and a custom risk scoring engine

# 🏦 Loan Default Prediction & Risk Scoring Engine

This project predicts whether a loan will be approved or rejected using machine learning, and also generates a risk score for each applicant based on the predicted probability of default. It includes explainable AI with SHAP to uncover how features influence decisions.

---

## 📁 Dataset

- Source: [Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- Features include: Gender, Married, Education, Credit History, Income, Loan Amount, etc.

---

## 🧠 ML Models Used

- Random Forest Classifier (main model)
- Optional: Logistic Regression, XGBoost (can be added for comparison)

---

## 🔧 Key Steps

1. **Data Cleaning** – Handled missing values using mode (categorical) and median (numerical)
2. **Encoding** – Used LabelEncoder and One-Hot Encoding for categorical variables
3. **Train-Test Split** – 80/20 split
4. **Model Training** – Trained a Random Forest classifier
5. **Evaluation** – Accuracy, F1-score, Classification Report
6. **Risk Scoring** – Scaled prediction probabilities to 0–100 risk scores
7. **Explainability** – Used SHAP to show how features influence model predictions
8. **Visualization** – Risk score distribution plot added for business interpretability

---

## 📊 Results

- **Accuracy:** ~78%
- **Top Features (SHAP):** Credit History, Applicant Income, Loan Amount, Married
- **Risk Score Engine:** Added custom scoring system for real-world use
- **SHAP Interaction Plot:** Demonstrates how pairs of features (e.g., Gender + Married) influence loan outcomes

---

## 📈 Visualizations

- SHAP Interaction Plot for explainability
- Risk Score Distribution Histogram

---

## 🚀 How to Run

1. Open the notebook: [Loan_Default_Prediction_Project.ipynb](./Loan_Default_Prediction_Project.ipynb)
2. Install required packages (`shap`, `scikit-learn`, `matplotlib`, `seaborn`)
3. Run all cells in order on Google Colab or Jupyter

---

## 💼 Skills Demonstrated

- Data preprocessing & feature engineering
- Supervised machine learning
- Model evaluation (accuracy, F1-score)
- SHAP model explainability
- Risk scoring logic for financial use cases
- Data visualization (Seaborn, Matplotlib)

---

## 📌 Author

Made with ❤️ by Tharun Kumar Malla Dinakaran
2nd Year Computer Science Student | Aspiring Data Scientist  
California State University San Marcos

