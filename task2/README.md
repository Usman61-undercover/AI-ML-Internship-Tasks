# 📦 Task 2: Customer Churn Prediction Using Random Forest

## 🎯 Objective
Build a machine learning pipeline to predict customer churn using the Telco Customer Churn dataset. The model uses a `RandomForestClassifier` and is fine-tuned using `GridSearchCV`.

## 📂 Dataset
- **Name:** Telco Customer Churn Dataset
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Target Variable:** `Churn` (Yes/No)
- **Features:** Demographic, account, and service-related features

## 🔧 Methodology

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Normalize numerical features

2. **Model Pipeline**
   - `ColumnTransformer` to preprocess data
   - `RandomForestClassifier` as the classifier
   - `GridSearchCV` for hyperparameter tuning

3. **Evaluation**
   - Classification Report
   - Accuracy Score
   - Confusion Matrix

4. **Model Export**
   - Trained pipeline saved using `joblib` for reuse

## 🧪 Evaluation Metrics

| Metric      | Description                        |
|-------------|------------------------------------|
| Accuracy    | Overall correctness of the model   |
| Precision   | True positives over predicted positives |
| Recall      | True positives over actual positives  |
| F1-Score    | Harmonic mean of precision and recall |

### ✅ Example Output

## 🧾 Files Included

- `churn_prediction_pipeline.ipynb` – Full code including training, tuning, and evaluation
- `churn_pipeline.joblib` – Trained and saved model
- `README.md` – Project documentation

## 🚀 Skills Gained

- Binary Classification
- Data Cleaning and Feature Engineering
- Model Evaluation Techniques
- Using Pipelines and GridSearchCV
- Model Saving with `joblib`

---
