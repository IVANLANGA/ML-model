# ITRI616 - Credit Card Fraud Detection Project

**Student Name:** Ivan
**Student Number:** 42264634
**Module Code:** ITRI616  
**Module Title:** Artificial Intelligence 1  
**Due Date:** 23 May 2025  
**Campus:** North-West University Vaal Triangle Campus  
**Examiner:** Melvin Kisten  

## Project Overview
This repository contains my submission for the ITRI616 Semester Project on Credit Card Fraud Detection using machine learning. The project demonstrates a systematic approach to data analysis, predictive modeling, and model performance assessment.

## Repository Structure
ITRI616-CreditCard-Fraud-Detection/
├── data/ # Contains dataset (or reference)
├── notebooks/ # Jupyter notebooks with full analysis
│ └── Fraud_Detection_Analysis.ipynb
├── reports/ # Project documentation
│ └── ITRI616_Project_Report.pdf
├── scripts/ # Python scripts (if applicable)
├── models/ # Saved models
│ ├── fraud_detection_model.pkl
│ ├── scaler.pkl
│ └── label_encoders.pkl
├── requirements.txt # Python dependencies
└── README.md # This file


## Dataset Information
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Characteristics:**
  - 284,807 transactions
  - 31 features (28 anonymized, Time, Amount, Class)
  - Binary target variable (Fraud = 1, Non-Fraud = 0)
  - Highly imbalanced dataset (0.172% fraud cases)

## Setup Instructions

### 1. Environment Configuration
```bash
# Clone repository
git clone https://github.com/[your-username]/ITRI616-CreditCard-Fraud-Detection.git
cd ITRI616-CreditCard-Fraud-Detection

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

2. Running the Analysis
Execute the Jupyter notebook:

jupyter notebook notebooks/Fraud_Detection_Analysis.ipynb

3. Reproducing Results
The notebook contains complete code for:

Data loading and exploration

Preprocessing pipeline

Model training and evaluation

Performance visualization