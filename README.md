# Fraud Detection System – Machine Learning Project

## Project Overview
This project aims to detect fraudulent credit card transactions using Machine Learning techniques.  
The goal is to build a model that can accurately classify transactions as fraudulent or legitimate based on historical data.

---

## Dataset
The dataset used in this project is the **Credit Card Fraud Detection Dataset** from Kaggle.

- Contains transactions made by European cardholders
- Highly imbalanced data
- 284,807 transactions
- Only 492 fraudulent cases

Target column:
- `Class`:  
  - 0 → Legitimate Transaction  
  - 1 → Fraudulent Transaction

---

## Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Project Workflow

The project followed these main steps:

1. **Data Loading and Exploration**
   - Understanding dataset structure
   - Checking missing values
   - Visualizing class distribution

2. **Data Preprocessing**
   - Handling imbalanced data
   - Feature scaling
   - Train-test splitting

3. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost

4. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

5. **Results Comparison**
   - Selecting the best performing model

---

## Evaluation Metrics

Models were evaluated using:

- Confusion Matrix  
- Classification Report  
- ROC Curve  
- AUC Score  

---

## Results

The final model achieved strong performance in detecting fraudulent transactions despite the imbalance in the dataset.

Key achievements:

- Successful handling of imbalanced data  
- High recall for fraud detection  
- Reliable and interpretable results  

---

## Files in This Repository

- `Fraud_Detection_Project.ipynb` → Main project notebook  
- `creditcard.csv` → Dataset (optional)  
- `README.md` → Project documentation  



