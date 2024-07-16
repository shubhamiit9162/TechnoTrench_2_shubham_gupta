Overview

This project is a Fraud Detection System designed to detect fraudulent credit card transactions using machine learning techniques. The system uses the Credit Card Transactions Fraud Detection Dataset to train and evaluate the model, aiming to accurately identify fraudulent transactions while minimizing false positives.

Dataset

The dataset used for this project is the Credit Card Transactions Fraud Detection Dataset, which contains anonymized features of transactions made by credit cardholders. The dataset includes both legitimate and fraudulent transactions, labeled for supervised learning.

Number of transactions: 284,807
Number of fraudulent transactions: 492
Features: 30 (28 anonymized features, 'Time', and 'Amount')
The dataset can be downloaded from Kaggle.

Project Structure

fraud-detection-system/
│
├── data/
│   └── creditcard.csv
├── notebooks/
│   └── Fraud Detection.ipynb
├── README.md
└── requirements.txt

Installation

Clone the repository:
git clone https://github.com/yourusername/fraud-detection-system.git
cd fraud-detection-system


Running the Notebook
To explore the data, preprocess it, and train the model, open and run the Fraud Detection.ipynb notebook:

jupyter notebook notebooks/Fraud Detection.ipynb

Description of the Notebook

The Fraud Detection.ipynb notebook includes the following steps:

Data Loading: Load the dataset from creditcard.csv.
Exploratory Data Analysis (EDA): Analyze the dataset to understand the distribution of features and identify any patterns or anomalies.
Data Preprocessing: Clean the data, handle missing values, normalize features, and split the dataset into training and testing sets.
Model Training: Train various machine learning models (e.g., Logistic Regression, Random Forest, XGBoost) to detect fraudulent transactions.
Evaluation: Evaluate the performance of the models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
Results: Summarize the findings and visualize the performance of the models using confusion matrices and ROC curves.
Requirements

The project requires the following Python libraries:

pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
