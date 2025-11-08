# Sentiment Analysis

## 📌 Project Overview

This project implements a **Sentiment Analysis model** that classifies text into **positive**(4) or **negative**(0) sentiments. It uses Natural Language Processing (NLP) techniques such as text preprocessing, tokenization, and machine learning classifiers to analyze sentiment from text data.

## 📂 Dataset

* Dataset: (https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download)
* Size:  100k samples extracted from 1.6M dataset
* Format: CSV file with text and sentiment labels.
* Labels: 0 = Negative, 1 = Positive

## ⚙️ Requirements

Install the following Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Moeez002/sentiment-analysis.git
   cd sentiment-analysis
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Sentiment_Analysis.ipynb
   ```
3. Run all cells to preprocess data, train the model, and evaluate results.

## 📊 Model & Results

* Algorithms used: Logistic Regression, Naive Bayes, SVM 
* Best Accuracy: **79%** (fill in with your result).
* Evaluation Metrics: Accuracy, Precision, Recall, F1-Score.

## 🔮 Future Improvements

* Experiment with deep learning models (LSTM, BERT).
* Deploy the model using Flask/Django/Streamlit.
* Use a larger dataset for better generalization.

## 📜 License

This project is open-source and available under the MIT License.

