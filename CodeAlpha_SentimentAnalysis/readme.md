# 😊 Sentiment Analysis & Emotion Detection using Machine Learning

## 📌 Project Overview
This project focuses on analyzing textual data to classify sentiment and detect emotions using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies user comments into **Positive, Neutral, or Negative** sentiments and identifies underlying emotions using the **NRC Emotion Lexicon**.

The notebook includes:
- Text Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Word Cloud Visualization
- TF-IDF Feature Extraction
- Machine Learning Model Training
- Model Evaluation
- Emotion Detection
- Results Visualization

---

## 📂 Dataset
- **Dataset:** `sentiment_data.csv`

The dataset contains user-generated text along with sentiment labels.

### Features
- Comment
- Sentiment
- Sentiment Label

**Target Variable:**
- Sentiment (Positive, Neutral, Negative)

---

## 🚀 Features

### 📝 Text Preprocessing
- Lowercase conversion
- Removal of punctuation
- Removal of numbers
- Stopword removal
- Text normalization
- Missing value handling

### 📊 Exploratory Data Analysis
- Dataset overview
- Sentiment distribution
- Text length analysis
- Word frequency analysis
- Word Clouds for each sentiment class

### 😊 Emotion Detection
Using the **NRC Emotion Lexicon**, the project detects emotions such as:

- Joy
- Trust
- Fear
- Anger
- Sadness
- Surprise
- Disgust
- Anticipation

---

## 🤖 Machine Learning Models Used

The following classification algorithms are trained and compared:

- Logistic Regression
- Multinomial Naive Bayes

Text features are extracted using:

- **TF-IDF Vectorization**

---

## 📊 Evaluation Metrics

Each model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

The best-performing model is selected based on classification performance.

---

## 📈 Visualizations

The notebook generates several visualizations including:

- Sentiment Distribution
- Text Length Distribution
- Word Clouds
- Confusion Matrix
- Model Performance Comparison
- Emotion Frequency Charts

---

## 🔮 Prediction

The trained model can predict the sentiment of new text comments and identify associated emotions using the NRC Emotion Lexicon.

Example:

```python
text = "The product quality is amazing and I absolutely love it!"
```

Output:

```
Predicted Sentiment: Positive

Detected Emotions:
Joy
Trust
Anticipation
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Scikit-learn
- NLTK
- Regular Expressions (re)

---

## 📁 Project Structure

```
Sentiment-Analysis-Emotion-Detection/
│
├── sentiment_data.csv
├── Sentiment_Analysis_Emotion_Detection.ipynb
├── README.md
├── requirements.txt
└── assets/ (optional)
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Sentiment-Analysis-Emotion-Detection.git
```

Move into the project directory:

```bash
cd Sentiment-Analysis-Emotion-Detection
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
wordcloud
nltk
```

---

## 📈 Workflow

1. Load Dataset
2. Clean and Preprocess Text
3. Perform Exploratory Data Analysis
4. Generate Word Clouds
5. Convert Text using TF-IDF
6. Train Machine Learning Models
7. Compare Model Performance
8. Select Best Model
9. Detect Emotions using NRC Lexicon
10. Visualize Results
11. Predict Sentiment for New Text

---

## 🎯 Future Improvements

- Deep Learning using LSTM/GRU
- Transformer Models (BERT, RoBERTa)
- Multilingual Sentiment Analysis
- Real-Time Social Media Analysis
- Streamlit Web Application
- Flask/FastAPI Deployment
- Explainable AI (SHAP/LIME)

---

## 👨‍💻 Author

**Abhijeet N G**

GitHub: https://github.com/your-username

---

## 📜 License

This project is intended for educational and learning purposes.