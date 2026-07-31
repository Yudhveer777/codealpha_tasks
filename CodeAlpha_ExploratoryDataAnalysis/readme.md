# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the quality of red wine using various Machine Learning classification algorithms. The dataset is analyzed, preprocessed, balanced using SMOTE, and trained on multiple models to identify the best-performing classifier.

The notebook includes:
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Preprocessing
- Feature Scaling
- Class Balancing
- Model Training & Evaluation
- Best Model Selection
- Model Saving & Prediction

---

## 📂 Dataset
- **Dataset:** WineQT.csv
- **Target Variable:** `quality`

The dataset contains physicochemical properties of wine such as:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

---

## 🚀 Features

### 📊 Exploratory Data Analysis
- Dataset overview
- Statistical summary
- Distribution plots
- Box plots
- Correlation Heatmap
- Count plots
- Bar plots

### 📈 Statistical Analysis
- Pearson Correlation Test
- Welch's t-test
- One-way ANOVA
- Outlier Detection (IQR Method)
- Class Imbalance Analysis

### 🧹 Data Preprocessing
- Missing value checking
- Duplicate removal
- Feature & target separation
- SMOTE for class balancing
- Robust Scaling
- Train-Test Split

---

## 🤖 Machine Learning Models Used

The following classification algorithms are trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)
- Gaussian Naive Bayes

---

## 📊 Evaluation Metrics

Each model is evaluated using:

- Training Accuracy
- Testing Accuracy
- Classification Report
- Accuracy Comparison Chart

The model with the highest test accuracy is automatically selected as the **Best Model**.

---

## 💾 Model Persistence

The notebook saves:

- Trained Best Model (`best_model.pkl`)
- Feature Scaler (`wine_scaler.pkl`)

using **Joblib**.

---

## 🔮 Prediction Example

The notebook demonstrates how to predict the quality of a new wine sample after scaling its features.

Example input:

```python
new_wine = [
    7.4, 0.7, 0.0, 1.9,
    0.076, 11.0, 34.0,
    0.9978, 3.51, 0.56, 9.4
]
```

Output:

```
Predicted Wine Quality: X
```

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Imbalanced-learn (SMOTE)
- Joblib

---

## 📁 Project Structure

```
Wine-Quality-Prediction/
│
├── WineQT.csv
├── Wine_Quality_Prediction.ipynb
├── best_model.pkl
├── wine_scaler.pkl
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Wine-Quality-Prediction.git
```

Move into the project directory:

```bash
cd Wine-Quality-Prediction
```

Install dependencies:

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
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
imbalanced-learn
joblib
rich
```

---

## 📈 Workflow

1. Load Dataset
2. Perform Exploratory Data Analysis
3. Statistical Hypothesis Testing
4. Detect Outliers
5. Remove Duplicates
6. Balance Classes using SMOTE
7. Scale Features
8. Split Data
9. Train Multiple Models
10. Compare Performance
11. Select Best Model
12. Save Model
13. Predict Wine Quality

---

## 🎯 Future Improvements

- Hyperparameter Tuning (GridSearchCV / RandomSearchCV)
- Cross Validation
- XGBoost & LightGBM Integration
- Feature Selection Techniques
- Flask/FastAPI Deployment
- Streamlit Web Application
- Docker Containerization

---

## 👨‍💻 Author

**Abhijeet N G**

GitHub: https://github.com/your-username

---

## 📜 License

This project is intended for educational and learning purposes.