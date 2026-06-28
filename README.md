# 📧 Email Classification Using Artificial Neural Networks (ANN)

An intelligent Email Classification system that automatically classifies emails as **Spam** or **Ham (Not Spam)** using **Artificial Neural Networks (ANN)** and **Natural Language Processing (NLP)** techniques.

---

## 📖 Project Overview

Email spam detection is one of the most important applications of Machine Learning and Natural Language Processing. This project implements an Artificial Neural Network (ANN) to classify emails into Spam or Ham categories.

The email text is preprocessed, converted into numerical vectors using **TF-IDF Vectorization**, and then classified using a fully connected Artificial Neural Network built with TensorFlow/Keras.

---

## 🚀 Features

- Email Text Classification
- Spam vs Ham Detection
- Text Preprocessing
- TF-IDF Vectorization
- Artificial Neural Network (ANN)
- Model Training and Prediction
- Accuracy Evaluation
- Confusion Matrix
- Classification Report

---

## 🛠️ Technologies Used

- Python
- Colab Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn

---

## 📂 Project Workflow

1. Import Required Libraries
  ```python
import pandas as pd
import numpy as np

from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import classification_report, accuracy_score, confusion_matrix

from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
```
3. Load Email Dataset
4. Clean and Preprocess Text
5. Encode Labels
6. Convert Text using TF-IDF Vectorizer
7. Split Dataset into Training and Testing Sets
8. Build ANN Model
9. Train the Model
10. Predict Email Classes
11. Evaluate Model Performance

---

## 🧠 ANN Architecture

- Input Layer
- Hidden Dense Layer(s)
- ReLU Activation
- Output Layer
- Sigmoid Activation
- Binary Classification

---

## 📊 Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Email-Classification-Using-ANN/
│
├── Email_Classification_Using_ANN.ipynb
├── README.md
├── spam1.csv
```

---

## 📷 Sample Prediction

Input Email

```
Congratulations!

You have won a FREE vacation package.

Click here to claim your prize.
```

Prediction

```
Spam
```

---

## 🎯 Applications

- Spam Email Filtering
- Email Security
- Business Email Automation
- Text Classification
- NLP Applications
- Intelligent Email Management

---

## 📈 Future Enhancements

- Hyperparameter Tuning
- Dropout Regularization
- Early Stopping
- LSTM & Bi-LSTM Models
- BERT-based Email Classification
- Flask Web Application
- Streamlit Deployment

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/Pattammal06/Email-Classification-Using-ANN.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook

```bash
colab notebook
```

4. Open

```
Email_Classification_Using_ANN.ipynb
```

5. Run all cells.

---

## 📌 Results

The ANN model successfully classifies emails into Spam and Ham categories using TF-IDF features and achieves reliable classification performance on the testing dataset.

---

## 👩‍💻 Author

**Pattammal M**

B.E. Computer Science and Engineering (Artificial Intelligence & Machine Learning)  

github-http://github.com/Pattammal06

---

