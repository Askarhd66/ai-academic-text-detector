<h1>🧠 Detecting Machine‑Generated Academic Text Using Supervised Learning</h1>

<h2>🎯 Project Overview</h2>
This project investigates whether supervised machine‑learning models can reliably detect AI‑generated academic essays, addressing a growing challenge in academic integrity. Using stylometric features and transformer‑based models, the study evaluates how effectively different classifiers distinguish between human‑written and machine‑generated text.

The project compares:
- <b>Stylometric models (Logistic Regression, SVM)</b>
- <b>Transformer models (BERT, RoBERTa)</b>
- <b>A perplexity‑based GPT‑2 baseline</b>
- <b>Cross‑domain generalisation using GPT‑2 web text</b>

<h2>🛠 Languages & Libraries</h2>
- Python (scikit‑learn, spaCy, NLTK, TextStat, PyTorch, HuggingFace Transformers)

<h2>Environments Used </h2>
- Jupyter Notebook

<h2>📊 Datasets Used</h2>
- Kaggle LLM Detect AI Text Dataset
- GPT‑2 Output Dataset

<h2>Key Findings</h2>
✔ <b>RoBERTa achieved the best overall performance</b>b>
 
 - Highest accuracy
 - Highest macro F1
 - Strongest ROC‑AUC
 - Most balanced confusion matrix

✔ <b>Stylometric models performed surprisingly well</b>
 - Logistic Regression and SVM captured meaningful writing‑style differences
 - Useful for interpretable, lightweight detection systems

✔ <b>GPT‑2 perplexity is a weak but informative baseline</b>
 - Works for short texts
 - Struggles with long academic essays

✔ <b>Cross‑domain performance drops significantly</b>
 - Models trained on academic essays struggle with informal web text
 - Highlights domain‑specific writing patterns
