# 🧠 AI/ML Internship Tasks  
This repository contains all tasks completed as part of my AI/ML Engineering Internship at DevelopersHub Corporation. Each task explores a unique aspect of machine learning including text classification, customer behavior prediction, and rule-based natural language processing.

---

## 📁 Tasks Overview

| Task No. | Task Name                            | Model/Method Used        | Type              | Output                                    |
|----------|--------------------------------------|--------------------------|-------------------|-------------------------------------------|
| Task 1   | News Topic Classifier                | BERT (Transformer)       | Text Classification | News Category (World, Sports, etc.)       |
| Task 2   | Customer Churn Prediction            | Random Forest            | Classification    | Predicts churn (Yes/No)                   |
| Task 3   | Auto Tagging Support Tickets         | Rule-based NLP           | Text Tagging      | Top 3 Relevant Tags per Ticket            |

---

# 📰 Task 1: News Topic Classifier Using BERT

## 🎯 Objective  
Fine-tune a transformer model (`bert-base-uncased`) to classify news headlines into topic categories using the AG News dataset.

## 📂 Dataset  
- **Name:** AG News Dataset  
- **Source:** [Hugging Face Datasets](https://huggingface.co/datasets/ag_news)  
- **Classes:** World, Sports, Business, Sci/Tech  

## 🔧 Methodology  
1. Install dependencies using `pip install transformers datasets gradio`.  
2. Tokenize using Hugging Face's `datasets` and `transformers`.  
3. Fine-tune `bert-base-uncased` with the `Trainer` API.  
4. Evaluate using **Accuracy** and **F1-score**.  
5. Deploy with **Gradio** UI.

## 📊 Evaluation Metrics  
- **Accuracy:** ~85–90%  
- **F1 Score:** ~0.85+  

## 🚀 Deployment  
Deployed using **Gradio** for live testing.  

## 📁 Files Included  
- `news_topic_classifier.ipynb`  
- `README.md`

## 🛠️ Tools & Libraries  
- `transformers`, `datasets`, `gradio`, `scikit-learn`, `PyTorch`  

## 📌 Skills Gained  
- NLP with Transformers  
- Fine-tuning BERT  
- Text classification  
- Web deployment with Gradio  

---

# 📦 Task 2: Customer Churn Prediction Using Random Forest

## 🎯 Objective  
Build a machine learning pipeline to predict customer churn using the Telco Customer Churn dataset.

## 📂 Dataset  
- **Name:** Telco Customer Churn  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Target:** `Churn` (Yes/No)  

## 🔧 Methodology  
1. Preprocess data (nulls, encode categoricals, scale numbers)  
2. Use `RandomForestClassifier`  
3. Hyperparameter tuning with `GridSearchCV`  
4. Export model with `joblib`  

## 🧪 Evaluation Metrics  

| Metric    | Description                         |
|-----------|-------------------------------------|
| Accuracy  | Correctness of predictions          |
| Precision | Correctly predicted positives       |
| Recall    | Sensitivity to actual positives     |
| F1-Score  | Balance between Precision & Recall  |

## 📁 Files Included  
- `churn_prediction_pipeline.ipynb`  
- `churn_pipeline.joblib`  
- `README.md`

## 🚀 Skills Gained  
- Binary classification  
- Data preprocessing & pipelines  
- Model tuning  
- Model serialization with `joblib`

---

# 🎫 Task 3: Auto Tagging Support Tickets (Rule-Based NLP)

## 🎯 Objective  
Automatically tag customer support tickets into categories using a lightweight rule-based NLP approach.

## 🧠 Methodology  
1. Define keyword-tag mappings  
2. Tokenize and lowercase text  
3. Score each ticket by tag relevance  
4. Assign top 3 tags

## 📂 Dataset  
- Manually defined support ticket examples  

**Example tickets:**  
- `"I want to reset my password."`  
- `"The billing amount is incorrect."`

## 📊 Output  

| Ticket                               | Tags                            |
|--------------------------------------|----------------------------------|
| My internet connection is down.      | Technical Issue                  |
| I want to reset my password.         | Login Problem                    |
| The billing amount is incorrect.     | Billing                          |

## 📁 Files Included  
- `Auto_Tagger.ipynb`  
- `README.md`

## 📌 Features  
- No API or ML model used  
- Customizable, fast, efficient  
- Ideal for low-resource environments

## 🚀 How to Run  
1. Clone this repo  
2. Open `Auto_Tagger.ipynb` in Colab  
3. Run cells and test outputs

## 💡 Insights  
- Zero-cost deployment  
- Rule-based text classification  
- Works well for small/medium ticket systems  

---

## 👤 Author  
**Usman Ameer**  
AI/ML Intern – DevelopersHub Corporation  
GitHub: [@Usman61-undercover](https://github.com/Usman61-undercover)
