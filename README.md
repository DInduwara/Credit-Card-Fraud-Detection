# Credit-Card-Fraud-Detection
📖 Project Description
This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset is highly imbalanced, with fraudulent cases being much rarer than legitimate ones. The main objective is to build models that can accurately identify fraud while minimizing false positives.



📂 Dataset
Source: Kaggle – Credit Card Fraud Detection
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

Contains transactions made by European cardholders in September 2013.

Features are numerical values obtained with PCA transformation (to protect privacy).

The dataset has 284,807 transactions, out of which only 492 are frauds (0.172%).



⚙️ Technologies Used

Python 3

Pandas, NumPy

scikit-learn

Matplotlib, Seaborn



🚀 Workflow


1.Data Exploration

 -Checked dataset shape, missing values, duplicates
 
 -Analyzed class imbalance

 
2.Preprocessing

 -Removed irrelevant columns (Time)
 
 -Standardized numerical features

 
3.Model Training

 -Logistic Regression
 
 -Random Forest

 
4.Evaluation

 -Accuracy (currently implemented)
 
 -(Recommendation: add Precision, Recall, F1, ROC-AUC for better insights due to class imbalance)
 


 📊 Results

Logistic Regression and Random Forest both achieved good results on accuracy, but Random Forest performed better in detecting fraud.

Since fraud detection requires minimizing false negatives, further work can include SMOTE oversampling and recall/precision analysis.



▶️ How to Run

Clone this repository:

git clone https://github.com/your-username/credit-card-fraud-detection.git

cd credit-card-fraud-detection


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook credit_card_fraud_detection.ipynb
