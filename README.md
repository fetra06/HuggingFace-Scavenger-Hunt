# 🤗 Hugging Face Sentiment Analysis with DistilBERT

This repository contains a beginner-friendly notebook that demonstrates how to perform **sentiment analysis** using a **pre-trained BERT model** from Hugging Face's Transformers library. The model is tested on real-world movie reviews from the IMDb dataset.

---

## 🚀 What You'll Learn

- How to load pre-trained models and tokenizers from Hugging Face
- How to define a prediction function using PyTorch
- How to test model predictions on custom and real-world reviews
- How to load datasets using the `datasets` library

---

## 📁 Notebook Included

| File | Description |
|------|-------------|
| [`HuggingFace_Sentiment_Analysis.ipynb`](HuggingFace_Sentiment_Analysis.ipynb) | Full step-by-step notebook showing model loading, predictions, and dataset evaluation |

---

## 🧠 Model Used

- **Model Name**: [`distilbert-base-uncased-finetuned-sst-2-english`](https://huggingface.co/distilbert-base-uncased-finetuned-sst-2-english)
- **Task**: Binary sentiment classification (positive or negative)
- **Dataset Used**: SST-2 (Stanford Sentiment Treebank)

---

## 📦 Requirements

```bash
pip install transformers datasets
