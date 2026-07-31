# Diabetes Prediction using Logistic Regression

This project implements a **Logistic Regression** model to predict diabetes using the **Diabetes Dataset**. The workflow includes data exploration, preprocessing, feature scaling, model training, evaluation, and interpretation of feature importance.

---

## 📌 Project Overview

The objective of this project is to build a binary classification model that predicts whether a patient has diabetes based on several medical measurements.

The project follows a complete machine learning pipeline:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Logistic Regression Model Training
- Model Evaluation
- ROC Curve & AUC Analysis
- Feature Importance Analysis

---

## 📂 Dataset

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |
| Outcome | 0 = Non-diabetic, 1 = Diabetic |

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview
- Missing value inspection
- Feature distributions
- Target class distribution
- Correlation heatmap

---

## ⚙ Data Preprocessing

The preprocessing pipeline includes:

- Feature selection
- Train-Test Split
- Standardization using StandardScaler

---

## 🤖 Model

The classification model used in this project is:

- Logistic Regression

---

## 📈 Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Area Under the Curve (AUC)

---

## 📉 Feature Importance

The coefficients of the Logistic Regression model were analyzed to determine the influence of each feature on diabetes prediction.

---

## 📁 Project Structure

```
diabetes-logistic-regression/
│
├── diabetes_logistic_regression.ipynb
├── diabetes.csv
└── README.md
```

---

## 📚 Libraries

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## 📌 Conclusion

Logistic Regression provides a simple, interpretable, and effective baseline model for diabetes prediction. The project demonstrates a complete machine learning workflow, including data preprocessing, model evaluation, ROC analysis, and feature importance interpretation.