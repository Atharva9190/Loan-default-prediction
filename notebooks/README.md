# Notebooks

This folder contains the main Jupyter/Colab notebook for the **Loan Default Prediction** project.

## 📂 Notebook Contents
**Loan_Default_Prediction.ipynb**
1. **Exploratory Data Analysis (EDA)**
   - Data exploration and summary statistics
   - Distribution plots and credit score analysis
   - Identification of class imbalance
2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering (FICO average score)
3. **Model Training & Evaluation**
   - Models: Logistic Regression, Random Forest, XGBoost, Gradient Boosting
   - Resampling: SMOTE, ADASYN, Random Undersampling
   - Hyperparameter tuning with GridSearchCV
4. **Performance Metrics**
   - Precision, Recall, and F1-score comparison
   - Focus on Recall to minimise false negatives

## ⚠️ Notes
- Designed for **Google Colab** or local Jupyter Notebook.
- Update dataset paths before running:
```python
data_path = "Data/processed/loan_data_processed.csv"
