📌 Objective
Build a machine learning model to predict whether a credit card customer will default on their payment using historical financial data.

📊 Dataset
Source: UCI Machine Learning Repository
Records: 30,000 customers
Target variable: default
0 → No default
1 → Default
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook
🔍 Approach
Loaded and explored real-world credit card data
Performed feature engineering on payment behavior
Applied stratified train-test split to preserve class balance
Trained classification models:
Logistic Regression
Random Forest
Evaluated models using:
Precision
Recall
F1-Score
ROC-AUC
📈 Results
Random Forest achieved higher ROC-AUC compared to Logistic Regression
Payment history and bill amounts were the most influential features
The model effectively distinguishes between defaulters and non-defaulters
🚀 How to Run
Clone the repository
Install dependencies:
pip install -r requirements.txt# Credit-Scoring-Model
