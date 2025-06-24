# Titanic Dataset - Data Cleaning & Preprocessing

## 📄 Description
This project focuses on cleaning and preprocessing the Titanic dataset to prepare it for analysis and machine learning. It includes handling missing values, encoding categorical variables, and scaling features.

## 📁 Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File: `Titanic-Dataset.csv`

## ✅ Tasks Performed
- Removed unnecessary columns (`Name`, `Ticket`, `Cabin`)
- Filled missing values in `Age`, `Fare`, and `Embarked`
- Converted categorical columns (`Sex`, `Embarked`) into numeric using one-hot encoding
- Scaled numeric features (`Age`, `Fare`) using StandardScaler
- Checked for outliers using boxplots

## 🛠️ Tools Used
- Python (Jupyter Notebook)
- Pandas, NumPy, Scikit-learn, Seaborn

## 📤 Output
The final cleaned dataset is ready for further analysis or machine learning model training.
