# Raw Data

This folder contains the **original, unprocessed dataset** for the Loan Default Prediction project.

## 📂 Contents
- `loan_data.csv` (Not included due to size restrictions — see download instructions below)

## 📊 Dataset Source
- **Name:** Loan Accepted and Rejected Dataset
- **Source:** Kaggle  
  [View Dataset](https://www.kaggle.com/datasets/krishnamurthi1703/housing-datasetloan-accepted-and-rejected)
- **Size:** ~400,000 rows, 25 columns
- **Features:**
  - Loan amount
  - Interest rate
  - Annual income
  - Debt-to-income ratio (DTI)
  - FICO score
  - Loan status (Fully Paid, Charged Off, Default, etc.)

## ⚠️ Note
Due to GitHub's file size limit and dataset licensing, the original data file is **not stored here**.  
Please download it from Kaggle and place it in this folder before running any scripts.

---

**Usage in Code:**
Place the raw dataset file here and reference it in the notebooks or scripts as:
```python
data_path = "Data/raw/loan_data.csv"
