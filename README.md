**📘 Propaganda Detection using NLP**

This project implements multiple NLP models to detect propaganda techniques in text.
It includes traditional machine learning, transformer-based models, span detection, and evaluation frameworks.

**🚀 Project Overview**

This project focuses on two main tasks:

Task 1 — Propaganda Technique Classification

Classify a given span into one of eight propaganda techniques using:

TF-IDF + Logistic Regression

BERT Sequence Classification

Task 2 — Span Detection and Technique Labelling

Identify spans containing propaganda and assign the correct label using:

Rule-Based Classifier

BERT BIO Tagging

BERT QA-Based Span Extraction

This project compares traditional ML, deep learning, and rule-based methods in a unified pipeline.

**Models Implemented**
| Model                        | Accuracy  | Macro F1 |
| ---------------------------- | --------- | -------- |
| TF-IDF + Logistic Regression | 35.5%     | 0.35     |
| BERT Sequence Classifier     | **50.6%** | **0.50** |

Task 2 Results
| Model          | Key Metric          | Score  |
| -------------- | ------------------- | ------ |
| BIO Tagging    | Token Accuracy      | 63%    |
| QA-Based Model | Full Match Accuracy | 4.83%  |
| Rule-Based     | F1-score            | 0.0044 |

**Technologies Used**

Python

HuggingFace Transformers (BERT)

PyTorch

scikit-learn

pandas, numpy

Matplotlib / Seaborn

**Dataset**

The dataset contains sentences with <BOS> and <EOS> tags identifying propaganda spans.
Training and validation data are included in the data/ folder.

**👩‍💻 Author**

Harshada Naik
Master’s in Data Science — University of Sussex
