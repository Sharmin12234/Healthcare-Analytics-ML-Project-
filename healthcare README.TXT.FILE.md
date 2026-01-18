
# Healthcare Data Analysis & Machine Learning 🏥

This project involves a comprehensive analysis of a healthcare dataset to predict patient medical conditions and test outcomes using machine learning.

## 📋 Project Overview
The goal of this project is to process patient demographic and medical data (such as Age, Gender, Blood Type, and Medication) to identify patterns and predict healthcare outcomes.

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- **Frameworks:** TensorFlow/Keras (Sequential Model used for Deep Learning)
- **Primary Algorithm:** Random Forest Classifier

## 📊 Dataset Features
The dataset consists of 55,500 patient records with the following key attributes:
- **Demographics:** Age, Gender, Blood Type
- **Medical Info:** Medical Condition, Medication, Test Results
- **Administrative:** Admission Type, Hospital, Insurance Provider, Billing Amount

## 🚀 Workflow
1. **Data Cleaning:** Handled categorical variables and verified that there are no missing values in the dataset.
2. **Exploratory Data Analysis (EDA):** Visualized distributions of medications and medical conditions using Seaborn and Matplotlib.
3. **Preprocessing:** Applied `OneHotEncoder` for categorical features and `StandardScaler` for numerical scaling.
4. **Model Training:** Trained a `RandomForestClassifier` and built a Neural Network using a `Sequential` model with 100 epochs.
5. **Evaluation:** Evaluated model performance using accuracy metrics on test data.

## 📈 Results
The final model achieved a test accuracy of approximately **21.5%**. While this reflects the complexity of predicting medical outcomes from general data, it serves as a foundation for more advanced feature engineering.

---
*This project is part of my 1-year data science journey archive.*