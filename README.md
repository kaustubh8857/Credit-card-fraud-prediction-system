# **Credit Card Fraud Detection – Machine Learning Project**

This repository contains a machine learning project focused on detecting fraudulent credit card transactions using data preprocessing, exploratory data analysis (EDA), and classification models. The goal is to develop an efficient fraud prediction system capable of identifying anomalies in highly imbalanced financial datasets.

---

## 🚀 **Project Overview**

Credit card fraud is a critical issue in the financial sector. Because genuine transactions heavily outnumber fraudulent ones, detecting fraud requires robust data handling and advanced classification techniques.

This project:

* Loads and preprocesses transaction data
* Handles **class imbalance**
* Performs **EDA** to understand key patterns
* Trains ML models for fraud detection
* Evaluates model performance using relevant metrics

---

## 📂 **Project Structure**

```
├── credit_card_Fraud_prediction.ipynb   # Main notebook  
├── README.md                            # Project documentation  
└── dataset/                             
     └── (Add dataset here or link externally)
```

---

## 📊 **Dataset**

* The dataset used contains anonymized credit card transaction details.
* It includes:

  * Numerical PCA-transformed features
  * Amount and time columns
  * A binary target column:

    * `0` → Legitimate
    * `1` → Fraud

> **Note:** Due to confidentiality, the dataset is NOT included. You can download the widely used public dataset from Kaggle: *"Credit Card Fraud Detection"*.

---

## 🛠️ **Technologies Used**

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn** (Visualizations)
* **Scikit-learn** (ML models & metrics)
* **SMOTE / Oversampling methods** (if used)
* **Jupyter Notebook**

---

## 🔍 **Key Steps Performed**

### ✔️ 1. Data Loading & Preprocessing

* Handling missing values
* Scaling features (StandardScaler)
* Treating class imbalance (SMOTE / undersampling)

### ✔️ 2. Exploratory Data Analysis

* Distribution plots
* Fraud vs non-fraud comparison
* Correlation heatmaps

### ✔️ 3. Model Training

Models typically include:

* Logistic Regression
* Random Forest
* Decision Tree
* XGBoost (optional)

### ✔️ 4. Evaluation Metrics

Since the dataset is imbalanced, focus is on:

* Precision
* Recall
* F1-score
* ROC-AUC score
* Confusion matrix

---

## 🧪 **How to Run**

1. Clone the repository:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook credit_card_Fraud_prediction.ipynb
```

4. Run all cells to reproduce results.

---

## 📌 **Future Improvements**

* Try deep learning models (ANN, LSTM)
* Use real-time anomaly detection
* Deploy model via API or web interface
* Improve feature engineering

---
