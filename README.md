# 💬 Context-Aware Sentiment Analysis Using RoBERTa and BiLSTM

<div align="center">

<img src="https://img.shields.io/badge/Python-3.10+-blue.svg" alt="Python 3.10+" />
<img src="https://img.shields.io/badge/PyTorch-2.x-orange.svg" alt="PyTorch" />
<img src="https://img.shields.io/badge/Transformers-HuggingFace-yellow.svg" alt="Hugging Face Transformers" />
<img src="https://img.shields.io/badge/Streamlit-App-ff4b4b.svg" alt="Streamlit" />

</div>

A context-aware sentiment analysis system that combines the power of RoBERTa for deep contextual embeddings and BiLSTM for sequential learning. This project is designed to detect sentiment in text with higher accuracy by capturing both semantic context and word-order dependencies.

## 🌟 Overview

This project presents a hybrid deep learning approach for sentiment analysis using:

- RoBERTa for contextualized text representation
- BiLSTM for learning forward and backward dependencies
- Streamlit for an interactive web interface
- Support for single-text and batch prediction

The system is suitable for NLP tasks such as:

- customer review analysis
- social media sentiment classification
- feedback mining
- opinion analysis in conversational text

## 📎 Project Links

- GitHub: https://github.com/kallaguntabalaji12
- LinkedIn: https://www.linkedin.com/in/balajikallagunta4425/
- Project ZIP (Google Drive): https://drive.google.com/drive/folders/19Lum3trtvb9tdWr-A1zM2Ie2Jzs_5fRe?usp=sharing

## 🎯 Objectives

- Build a context-aware sentiment classification model
- Extract rich contextual embeddings using RoBERTa
- Capture sequential dependencies using BiLSTM
- Classify text into sentiment labels with confidence scores
- Provide an interactive dashboard for predictions

## 🧠 Model Architecture

The hybrid architecture integrates the following components:

1. RoBERTa Tokenizer
   - Converts input text into tokens and attention masks
2. RoBERTa Encoder
   - Produces contextual embeddings of size 768
3. BiLSTM Layer
   - Captures both past and future context in text sequences
4. Dropout Layer
   - Reduces overfitting during training
5. Fully Connected Layer
   - Maps learned features to sentiment classes
6. Softmax Output
   - Generates probability scores for each class

## 📊 Supported Datasets

This application supports the following datasets:

- Twitter US Airline Sentiment Dataset
  - Positive
  - Negative
  - Neutral
- Stanford SST-2 Dataset
  - Positive
  - Negative

## ⚙️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- RoBERTa
- BiLSTM
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## ✨ Key Features

- Context-aware sentiment classification
- Hybrid RoBERTa + BiLSTM model
- Single text prediction
- Batch CSV prediction
- Confidence score and probability distribution
- Interactive Streamlit dashboard
- Model evaluation and performance metrics

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/kallaguntabalaji12/Context-Aware-Sentiment-Analysis-Using-RoBERTa-and-BiLSTM
cd Context-Aware-Sentiment-Analysis-Using-RoBERTa-and-BiLSTM
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run app.py
```

## 🧪 Expected Output

The application predicts the sentiment of the input text and displays:

- Predicted sentiment label
- Prediction confidence
- Probability distribution across classes

Example:

- Positive / Negative / Neutral
- Confidence score in percentage
- Sentiment probabilities

## 🗂️ Project Structure

```text
Context-Aware-Sentiment-Analysis-Using-RoBERTa-and-BiLSTM/
├── app.py
├── model.py
├── train.py
├── utils.py
├── requirements.txt
├── README.md
├── data/
└── results/
```

> Note: The exact project structure may vary depending on the final repository version.

## 🏆 Academic / Research Context

- Project Title: Context-Aware Sentiment Analysis Using RoBERTa and BiLSTM
- Domain: Natural Language Processing (NLP)
- Area: Deep Learning and Sentiment Classification
- Application: Text and review sentiment analysis

## 📌 Summary

This repository demonstrates how combining transformer-based contextual embeddings with recurrent sequence models can improve sentiment classification accuracy. It is a practical and research-oriented project that bridges modern NLP methods with a user-friendly interactive application.

## 🙋‍♂️ Author

Balaji Kallagunta

Connect with me on LinkedIn: https://www.linkedin.com/in/balajikallagunta4425/

---

If you want, I can also make this README even more premium by adding:

- a custom project banner image
- a screenshot section
- a better architecture diagram
- a polished "How it works" flowchart
- a GitHub badges section for downloads and stars
