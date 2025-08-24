# 🧠 Heart Disease Prediction with Random Forest

This project uses clinical and demographic data to predict the presence of heart disease using a Random Forest classifier. It’s part of my biomedical AI portfolio focused on precision medicine and data-driven healthcare.

## 📊 Dataset

- Source: [Heart Disease Dataset (UCI version) by ketangangal on Kaggle](https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci)
- File used: `HeartDiseaseTrain-Test.csv` (113.4 kB)
- Description: Contains anonymized patient data with 14 clinical features and 1 target label for binary classification of heart disease risk.

## 🧪 Modeling Pipeline

- Data preprocessing: handled missing values, encoded categorical features, scaled numerical variables
- Feature selection: identified top predictors using Random Forest’s built-in importance metrics
- Model training: trained Logistic Regression and Random Forest classifiers
- Evaluation: assessed performance using accuracy, precision, recall, F1 score, confusion matrix, ROC curve, and AUC score

## ✅ Results

- **Random Forest Accuracy**: 98.5%
- **Precision**: 100%
- **Recall**: 97.1%
- **F1 Score**: 98.6%
- **AUC Score**: 1.00 (Perfect classification)
- **Confusion Matrix**: Only 3 false negatives, 0 false positives
- **Feature Importance**: Max heart rate, age, oldpeak, and chest pain type were top predictors

## 📈 Visuals

Visualizations are included in the notebook:
- ROC Curve showing perfect separation between classes
- Feature Importance plot highlighting key clinical predictors

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

`#machine-learning` `#biomedical-ai` `#heart-disease` `#data-science` `#jupyter-notebook` `#precision-medicine`

## 📎 Notebook Preview

If GitHub preview fails, view the notebook on [nbviewer](https://nbviewer.org/github/MureedSajjad/heart-disease-prediction/blob/main/Heart_Disease_Prediction_RF_BiomedicalAI.ipynb)
