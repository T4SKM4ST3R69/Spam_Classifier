#  Spam Detection System

A machine learning-based spam detection system that classifies SMS messages as spam or ham (legitimate) using Logistic Regression and Naive Bayes algorithms with an interactive Streamlit web interface.

##  Project Overview

This project implements a complete spam detection pipeline including:

- Data preprocessing with text cleaning
- Dataset balancing using weighted sampling
- Training of Logistic Regression and Naive Bayes classifiers
- Model persistence for future use
- Interactive web application for real-time predictions


## Features

- **Dual Model Support**: Choose between Logistic Regression and Naive Bayes
- **Text Preprocessing**: Automatic text cleaning and normalization
- **Balanced Training**: Handles imbalanced datasets using weighted sampling
- **Confidence Scoring**: Provides prediction confidence percentages
- **Interactive UI**: User-friendly Streamlit web interface
- **Model Persistence**: Save and load trained models
- **Real-time Prediction**: Instant spam/ham classification


## Project Structure

```
spam-detection/
│
├── spam.csv                         
├── streamlit_app.py    
├── requirements.txt              
├── README.md                         
├── tfidf_vectorizer.joblib
├── logistic_regression_model.joblib
└── naive_bayes_model.joblib

```


## 🛠️ Installation

1. **Clone the repository**

```bash
git clone <repository-url>
cd spam-detection
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```


