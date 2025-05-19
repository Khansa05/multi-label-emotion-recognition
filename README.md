# Multi-Label Emotion Recognition from Text

This project aimed to build a system for detecting multiple emotional tones (e.g., joy, sadness, anger) in text using the GoEmotions dataset and transformer-based models (like BERT). 

---

## 📌 Objective

To fine-tune a transformer model for **multi-label emotion classification** using:
- GoEmotions dataset by Google
- Transformer architecture (BERT)
- Evaluation using F1 Score and Hamming Loss

---

## 🧪 Attempted Workflow

1. Loaded GoEmotions dataset.
2. Handled class imbalance.
3. Fine-tuned `BERTForSequenceClassification` for multi-label classification.
4. Encountered various dependency and compatibility issues in Google Colab (see report).

---

## ❗ Problems Faced

- `TrainingArguments` raised unexpected keyword errors.
- Issues with `tokenizers` wheel build.
- Compatibility conflict with `transformers`, `sentence-transformers`, and `tokenizers`.
- `Cache` import errors in the latest `transformers` versions.

---

## 📄 Report

A detailed explanation of all steps, code attempts, and issues is provided in the report:

📄 `Multi_Label_Emotion_Recognition_Report.docx`

---

## 📌 Outcome

Due to unresolved compatibility issues, the system could not be successfully implemented at this time. We have documented all findings and errors for future troubleshooting and improvement.

---

## Clone Repository

```bash
git clone https://github.com/Khansa05/multi-label-emotion-recognition.git
cd multi-label-emotion-recognition
pip install -r requirements.txt

