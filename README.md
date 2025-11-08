# roberta-mental-health-classification
🤖 A RoBERTa-based text classifier for mental health status detection (Normal vs. Abnormal and Multi-Class), built with PyTorch and Hugging Face.


# RoBERTa Mental Health Text Classification

This project uses a RoBERTa model to classify text statements into different mental health categories. It's trained on the "Sentiment Analysis for Mental Health" dataset to identify sentiments related to depression, anxiety, suicide, and more.

This repository provides two different classification models:

* **`Binary_classification.ipynb`**: Classifies text as either **Normal** or **Abnormal**.
* **`Multi_class.ipynb`**: Classifies text into multiple categories (**Normal, Depression, Suicidal, Anxiety, Bipolar,** etc.).

The models are built using PyTorch and the Hugging Face `transformers` library.

---

> ⚠️ **Disclaimer: Not a Medical Tool**
>
> This is a technical NLP project for educational and research purposes. The models are **not** a substitute for professional medical advice, diagnosis, or treatment. If you or someone you know is struggling with mental health, please seek help from a qualified professional.

---

## 🚀 Features

* **Model:** Utilizes the powerful `roberta-base` transformer model.
* **Framework:** Built entirely in PyTorch.
* **Library:** Leverages the Hugging Face `transformers` library for easy model loading and tokenization.
* **Two Modes:** Includes complete notebooks for both:
    * Binary classification (Normal vs. Abnormal)
    * Multi-class classification (Normal, Depression, Suicidal, etc.)
* **Evaluation:** Generates detailed classification reports and confusion matrices to assess model performance.
* **Inference:** Provides a simple function to test your own statements on the trained model.

## 📊 Example Results

The notebooks will generate a confusion matrix to visualize the model's performance. Here is an example of the output for the multi-class model:



## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/anchalnagwanshi/roberta-mental-health-classification.git]
cd roberta-mental-health-classification
