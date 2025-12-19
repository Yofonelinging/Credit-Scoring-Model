# Credit Scoring Model

## 📌 Objective
Build a machine learning model to predict whether a credit card customer will
default on their payment using historical financial data.

---

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Records: 30,000 customers
- Target variable: `default`
  - 0 → No default
  - 1 → Default

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Approach
1. Loaded and explored real-world credit card data
2. Performed feature engineering on payment behavior
3. Applied stratified train-test split to preserve class balance
4. Trained classification models:
   - Logistic Regression
   - Random Forest
5. Evaluated models using:
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC

---

## 📈 Results
- Random Forest achieved higher ROC-AUC compared to Logistic Regression
- Payment history and bill amounts were the most influential features
- The model effectively distinguishes between defaulters and non-defaulters

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
