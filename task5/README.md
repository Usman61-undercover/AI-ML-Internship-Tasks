# 🎫 Task 5: Auto Tagging Support Tickets (Rule-Based NLP)

This repository contains the solution for **Task C** of the DevelopersHub Corporation AI/ML Engineering – Advanced Internship. The goal of this task is to automatically tag support tickets into appropriate categories using efficient and lightweight natural language processing (NLP) techniques — without the use of APIs or heavy machine learning models.

---

## ✅ Objective

Automatically classify customer support tickets into 3 relevant categories based on their content using simple keyword-based matching.

---

## 🧠 Methodology

Instead of relying on large language models or fine-tuning with APIs, this project uses a **rule-based NLP approach**:

- Define keyword mappings for each support tag
- Convert each ticket to lowercase
- Check which keywords appear in each ticket
- Assign the top 3 most relevant tags based on keyword matches

---

## 📁 Dataset

We used a **manually defined list of sample support tickets** to simulate realistic customer queries.

Example tickets:
- `"I want to reset my password."`
- `"My internet connection is down."`
- `"The billing amount is incorrect."`

---

## ⚙️ Implementation Steps

1. Define support ticket samples
2. Create a tag-to-keywords mapping
3. Build a scoring function that matches tickets to tags
4. Return top 3 tags based on match score
5. Display results in a table

---

## 📊 Output

| Ticket                                 | Tags                              |
|----------------------------------------|------------------------------------|
| My internet connection is down.        | Technical Issue                   |
| I want to reset my password.           | Login Problem                     |
| The billing amount is incorrect.       | Billing                           |
| My app crashes on startup.             | Technical Issue                   |
| I can't log into my account.           | Login Problem, Account            |

---

## 🧪 Evaluation

Since this is a rule-based task:
- No training or evaluation metrics like accuracy/F1 are needed
- You can easily test performance by adding new tickets and verifying correctness

---

## 🚀 How to Run

You can run this notebook directly in **Google Colab** or any local Jupyter environment:

1. Clone this repository
2. Open the notebook file `Auto_Tagger.ipynb`
3. Run all cells
4. View the output table or export as CSV

---

## 💡 Insights

- No API keys or internet needed
- Extremely fast and efficient
- Easily customizable
- Works well for small/medium-sized support systems

---

## 🏁 Final Summary

This lightweight task demonstrates a practical and computationally efficient way to classify support queries — ideal for quick demos, small businesses, or low-resource environments.

---
