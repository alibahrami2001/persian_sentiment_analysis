# Emotion Classifier 😄😢 — Snappfood Sentiment Analysis

This project implements a simple yet effective **emotion classification model** that detects emotions in user reviews. The dataset includes user comments from Snappfood labeled as either **HAPPY** or **SAD**.

## 📁 Files Included
- `emotion_classifier.ipynb`: The full notebook with data preprocessing, embeddings generation using Transformers, and classifier training.
- `Snappfood - Sentiment Analysis.csv`: The dataset used for training and testing, containing user reviews with emotion labels.

## 🛠️ Technologies Used
- Python
- PyTorch
- HuggingFace Transformers
- pandas
- scikit-learn

## 🚀 How to Use
1. Open the notebook in Google Colab or your local Jupyter environment.
2. Run all cells in order.
3. The model will classify new input texts as either **HAPPY** or **SAD**.

## 🎯 Project Goal
To demonstrate a simple NLP pipeline for **emotion detection** using pre-trained Transformer models to generate sentence embeddings, followed by a custom classifier.

## ⚠️ Notes
The embeddings (`train_embeddings.pt`, `test_embeddings.pt`) are not included for size considerations. You can regenerate them by uncommenting and running the appropriate cells in the notebook.

---

Feel free to fork this repo.
