# 📰 Task 1: News Topic Classifier Using BERT

## 🎯 Objective
Fine-tune a transformer model (`bert-base-uncased`) to classify news headlines into topic categories using the AG News dataset.

## 📂 Dataset
- **Name:** AG News Dataset
- **Source:** [Hugging Face Datasets](https://huggingface.co/datasets/ag_news)
- **Classes:** World, Sports, Business, Sci/Tech

## 🔧 Methodology
1. Install dependencies using `pip install transformers datasets gradio`.
2. Load and tokenize the dataset using Hugging Face's `datasets` and `transformers`.
3. Fine-tune the `bert-base-uncased` model using the `Trainer` API with evaluation and training splits.
4. Evaluate the model using **Accuracy** and **F1-score**.
5. Deploy using **Gradio** for interactive predictions.

## 📊 Evaluation Metrics
- **Accuracy:** ~85–90%
- **F1 Score:** ~0.85+

## 🚀 Deployment
Model deployed using **Gradio** for testing with live inputs in a simple UI.

## 📁 Files Included
- `news_topic_classifier.ipynb`: Full notebook with training, evaluation, and deployment
- `README.md`: Project documentation and results

## 🛠️ Tools & Libraries
- `transformers`
- `datasets`
- `gradio`
- `scikit-learn`
- `PyTorch`

## 📌 Skills Gained
- Natural Language Processing with Transformers
- Fine-tuning Pretrained BERT Models
- Dataset Tokenization & Padding
- Evaluation using Accuracy & F1
- Lightweight Web Deployment with Gradio
