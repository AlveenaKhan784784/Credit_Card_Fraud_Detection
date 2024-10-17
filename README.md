# Credit_Card_Fraud_Detection

# Objective
This project aims to detect fraudulent credit card transactions using machine learning techniques. The goal is to build a model that can identify fraudulent transactions to help prevent financial losses.

 Source : [Link to dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
 
## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Model Used**:Random Forest

## Project Workflow
1. **Data Collection**:
   - Retrieved the credit card transaction dataset from Kaggle.
2. **Data Preprocessing**:
   - Handled missing values (if any).
   - Scaled the `Amount` feature and transformed the `Time` feature for model compatibility.
   - Split the dataset into training and testing sets.
3. **Feature Engineering**:
   - Explored feature importance and created new features as necessary.
   - Balanced the dataset using techniques like **SMOTE (Synthetic Minority Over-sampling Technique)**.
4. **Modeling**:
   - Trained machine learning model including  **Random Forest**
   - Tuned hyperparameters using cross-validation to improve model performance.
5. **Model Evaluation**:
   - Evaluated models using metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.
   - Used confusion matrices to visualize the performance of the models.
6. **Results Visualization**:
   - Visualized model performance metrics and feature importance.
