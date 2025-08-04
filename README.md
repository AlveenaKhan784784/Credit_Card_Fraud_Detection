# Credit Card Fraud Detection

## Objective
This project aims to detect fraudulent credit card transactions using machine learning techniques. The goal is to build a robust model capable of identifying fraudulent activity and helping prevent financial losses for banks and customers.

**Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Model Used**: Random Forest Classifier
- **Imbalance Handling**: SMOTE (Synthetic Minority Over-sampling Technique)

---

## Project Workflow

### 1. Data Collection
- Retrieved the dataset from Kaggle containing anonymized credit card transactions with binary fraud labels.

### 2. Data Preprocessing
- Checked and handled missing values (if any).
- Scaled the `Amount` feature and transformed `Time` for better model input.
- Performed a stratified train-test split to preserve class distribution.

### 3. Feature Engineering
- Analyzed feature importance using Random Forest.
- Balanced the dataset using **SMOTE** to address severe class imbalance (~0.17% fraud cases).

### 4. Model Training
- Trained a **Random Forest** classifier.
- Applied cross-validation and hyperparameter tuning to optimize performance.

### 5. Model Evaluation
- Evaluated performance using:
  - **Confusion Matrix**
  - **Accuracy**, **Precision**, **Recall**, **F1-Score**
  - **ROC-AUC Score**
- Focused on improving recall for the fraud class due to its critical importance.

### 6. Results Visualization
- Plotted confusion matrix, ROC curve, and feature importance.

---

## Key Results
- Achieved high **ROC-AUC**, strong **precision and recall** for detecting fraudulent transactions.
- Random Forest performed well under SMOTE-balanced data.

---

## Future Improvements (Optional)
- Try advanced models like **XGBoost** or **LightGBM**.
- Build a simple **Streamlit** or **Flask** app to make predictions.
- Deploy the model via API or web interface.
