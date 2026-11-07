💬 Context-Aware Sentiment Analysis Using RoBERTa and BiLSTM

📌 Project Overview

This project presents a hybrid deep learning approach for context-aware sentiment analysis using RoBERTa (Robustly Optimized BERT Pretraining Approach) and BiLSTM (Bidirectional Long Short-Term Memory). The system analyzes textual data and classifies sentiments based on contextual information. By combining the powerful contextual representations of RoBERTa with the sequential learning capabilities of BiLSTM, the model captures both semantic context and temporal dependencies in sentences.
The project provides an interactive web application built using Streamlit for real-time and batch sentiment prediction.

📎 Connect with Me

GitHub: https://github.com/kallaguntabalaji12
LinkedIn: https://www.linkedin.com/in/balajikallagunta4425/

📥 Large Project Files / Download

The full project ZIP file is available here:
https://drive.google.com/drive/folders/19Lum3trtvb9tdWr-A1zM2Ie2Jzs_5fRe?usp=sharing

🎯 Objectives:
To develop a context-aware sentiment analysis system.
To extract contextual word representations using RoBERTa.
To capture forward and backward contextual dependencies using BiLSTM.
To classify text into different sentiment categories.
To provide an interactive interface for sentiment prediction.

🧠 Model Architecture:
The proposed hybrid architecture consists of:
RoBERTa Tokenizer: Converts input text into token IDs.
RoBERTa Encoder: Extracts contextual embeddings (768 dimensions).
Bidirectional LSTM: Captures sequential dependencies in both directions.
Dropout Layer: Helps reduce overfitting.
Fully Connected Layer: Performs sentiment classification.
Softmax: Produces sentiment probability scores.

📊 Datasets:

The application supports two datasets:
Twitter US Airline Dataset: Positive, Negative, and Neutral sentiment classification.
Stanford SST-2 Dataset: Positive and Negative sentiment classification.


⚙️ Technologies Used:

Python
PyTorch
RoBERTa
BiLSTM
Hugging Face Transformers
Streamlit
Pandas and NumPy
Scikit-learn
Matplotlib and Seaborn


✨ Key Features:

Context-aware sentiment classification.
Hybrid RoBERTa-BiLSTM deep learning architecture.
Support for multiple datasets.
Single-text sentiment prediction.
Batch prediction using CSV files.
Sentiment confidence scores and probability distribution.
Model performance evaluation.
Interactive Streamlit dashboard.

🚀 Application Modules:
Problem Statement
Sample Training Data
Data Preprocessing
Model Training
Testing and Results
Sentiment Prediction

📦 Installation

Clone the repository:
git clone https://github.com/kallaguntabalaji12/Context-Aware-Sentiment-Analysis-Using-RoBERTa-and-BiLSTM

Navigate to the project directory:
cd Context-Aware-Sentiment-Analysis-RoBERTa-BiLSTM


Install dependencies:
pip install -r requirements.txt
Run the Streamlit application:
streamlit run app.py


🔮 Expected Output:
The application predicts the sentiment of the input text and displays:

Predicted sentiment (Positive / Negative / Neutral, depending on the dataset).

Prediction confidence.

Sentiment probability distribution.


🎓 Academic Project:

Project Title: Context-Aware Sentiment Analysis Using RoBERTa and BiLSTM

Domain: Natural Language Processing (NLP) and Deep Learning

Application: Text Sentiment Classification
