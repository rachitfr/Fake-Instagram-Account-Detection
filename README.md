# Fake Instagram Account Detection System  
End-to-End Machine Learning & Analytics Project

A production-style data science project that detects fake Instagram accounts using behavioral, profile, and activity-based features. The project combines Exploratory Data Analysis, Feature Engineering, Deep Learning, and Business Intelligence (Power BI) to build a complete analytical and predictive solution.

---

## Business Problem

Fake Instagram accounts are widely used for spam, scams, impersonation, and artificial engagement. Manual moderation is not scalable.

This system automatically classifies Instagram accounts as **Fake** or **Genuine** using machine learning, helping platforms improve security and trust.

---

## Project Objectives

- Analyze behavioral patterns of fake vs genuine accounts  
- Engineer meaningful predictive features  
- Build a deep learning classification model  
- Visualize insights using Power BI  
- Deliver an end-to-end data science project

---

## Dataset

Input files:

- train.csv  
- test.csv  

Target column:

- fake  
  - 1 → Fake Account  
  - 0 → Genuine Account  

Key features:

- profile pic  
- nums/length username  
- fullname words  
- nums/length fullname  
- name==username  
- description length  
- external URL  
- private  
- #posts  
- #followers  
- #follows  

---

## Approach

1. Data Cleaning & Validation  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Feature Scaling  
5. Train/Test Split  
6. Deep Learning Model Training  
7. Model Evaluation  
8. Business Dashboard Development  

---

## Technology Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  
- Power BI  
- JupyterLab  

---

## Machine Learning Model

- Feedforward Neural Network  
- ReLU Activation in Hidden Layers  
- Softmax Output Layer  
- Categorical Cross-Entropy Loss  
- Adam Optimizer  

The model learns non-linear relationships between account attributes and fake account behavior.

---

## Power BI Dashboard

The dashboard answers:

- Fake vs Genuine Account Distribution  
- Username Numeric Pattern Comparison  
- Followers Distribution  
- External URL Usage  
- Name Equals Username Behavior  
- Private vs Public Accounts  

Designed for executive-level readability and operational monitoring.

---

## Key Insights

- Fake accounts tend to contain more numbers in usernames  
- Fake accounts usually have very low post counts  
- Using the same value for name and username is a strong fake indicator  
- Accounts with suspicious external URLs show higher fake concentration  
- Followers distribution is highly skewed and requires log-scale analysis  

---

## Project Structure
'''
Fake-Instagram-Account-Detection/
│
├── data/
│   └── raw/
│       ├── train.csv
│       └── test.csv
│
├── notebooks/
│   └── 01_eda_modeling.ipynb
│
├── dashboard/
│   └── Instagram_Accounts_Analysis.pbix
│
├── reports/
│   └── Dashboard_Export.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
'''
---

## Business Value

- Reduces manual moderation workload

- Helps detect spam networks early

- Improves platform trust and user safety

- Demonstrates real-world ML deployment readiness

---

## Author
Rachit Vats
