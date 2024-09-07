
# IndoBERT-LSTM Text Classification

This project implements a **text classification model** that combines **IndoBERT** embeddings with an **LSTM (Long Short-Term Memory)** network. It is designed to process and classify text data in the **Indonesian language**, specifically hoax and non-hoax news.

---

## ✨ Features
- **IndoBERT embeddings** fine-tuned for Indonesian text.
- **LSTM architecture** for sequence learning and efficient text classification.
- Evaluation metrics include **Accuracy**, **Precision**, **Recall**, and **F1 Score**.

---

## 📊 Dataset

The dataset consists of hoax and non-hoax news articles obtained through **web scraping** from Indonesian news websites.

Key preprocessing steps:
- **Tokenization** using IndoBERT tokenizer.
- **Stopword removal** using NLTK for Indonesian text.

---

## 🧠 Model Architecture

The model architecture includes:
- **IndoBERT embeddings** to generate dense vector representations of text.
- An **LSTM** layer to capture sequence dependencies.
- **Dropout layers** to reduce overfitting.
- **Dense layers** with softmax activation for multi-class classification.

---

## 📈 Results

The performance of the model is evaluated based on key metrics:
- **Accuracy**: Overall classification accuracy.
- **F1 Score**: A balance between Precision and Recall.

Results are visualized using:
- **Confusion Matrix**
- **Accuracy and Loss plots** over epochs.

