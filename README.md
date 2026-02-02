# Code-Mixed Sentiment Analysis using HiEn-mBERT+

A lightweight transformer-based approach for **Hindi–English (Hi-En) code-mixed sentiment analysis**, designed to handle noisy social media text with mixed scripts and transliteration.

## 📌 Project Overview

Code-mixed text (e.g., Hindi–English) is common on social media but challenging for NLP models due to spelling variations, transliteration, and language switching.  
This project proposes **HiEn-mBERT+**, a fine-tuned multilingual BERT-based model optimized for sentiment classification on Hindi–English code-mixed data.

The work was carried out during a **Research Internship at IIIT Ranchi (May 2025 – July 2025)**.

## 🧠 Key Contributions

- Developed a **lightweight BERT-based model** tailored for Hindi–English code-mixed sentiment analysis  
- Designed preprocessing pipelines to handle:
  - Code-mixing and transliteration
  - Noisy social media text
- Fine-tuned multilingual transformer models for improved contextual understanding
- Conducted comparative evaluation with classical machine learning baselines

## 📊 Results of mBERT

| Metric        | Score |
|---------------|-------|
| Accuracy      | **84.8%** |
| F1-Score      | **84.5%** |

- The proposed model **outperformed classical ML baselines**
- Demonstrated better robustness on code-mixed text compared to traditional text-based approaches

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **mBERT / XLM-RoBERTa**
- **scikit-learn**
- **NumPy, Pandas**

## 📂 Project Structure

```text
├── data/
│   ├── raw/
│   └── processed/
├── preprocessing/
│   ├── clean_text.py
│   └── language_handling.py
├── models/
│   └── hien_mbert_plus.py
├── training/
│   └── train.py
├── evaluation/
│   └── evaluate.py
├── results/
│   └── metrics.json
├── requirements.txt
└── README.md
