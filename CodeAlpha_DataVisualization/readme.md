# 🚦 Traffic Congestion Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing urban traffic data to identify peak traffic hours and predict congestion levels using Machine Learning. The dataset is processed through feature engineering, exploratory data analysis, and a Random Forest model to generate accurate congestion predictions and traffic insights.

The notebook includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Peak Hour Analysis
- Traffic Pattern Visualization
- Congestion Labeling
- Machine Learning Model Training
- Model Evaluation
- Traffic Congestion Prediction
- Dashboard Summary

---

## 📂 Dataset
- **Dataset:** `traffic.csv`

The dataset contains traffic observations with features such as:

- Date & Time
- Junction Number
- Vehicle Count
- Day of Week
- Hour of Day
- Month
- Weekend Indicator

---

## 🚀 Features

### 📊 Exploratory Data Analysis
- Dataset overview
- Traffic distribution
- Vehicle count analysis
- Peak traffic hour identification
- Junction-wise traffic analysis
- Heatmap visualization
- Traffic trend visualization

### ⚙️ Feature Engineering
- DateTime conversion
- Hour extraction
- Day of Week extraction
- Month extraction
- Weekend identification
- Time-based traffic features

### 🚗 Traffic Analysis
- Overall Peak Hour Detection
- Peak Hour by Junction
- Day vs Hour Heatmap
- Congestion Categorization

---

## 🤖 Machine Learning Model

The project uses:

- **Random Forest Regressor**

The model predicts expected traffic volume and congestion based on historical traffic patterns.

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- R² Score
- Actual vs Predicted Analysis
- Feature Importance

---

## 📈 Visualizations

The notebook generates several visualizations including:

- Traffic Distribution Charts
- Junction-wise Peak Hour Graphs
- Day-of-Week × Hour Heatmap
- Feature Importance Plot
- Dashboard Summary

---

## 🔮 Prediction

The trained model predicts traffic congestion for different junctions during peak hours, helping identify high-traffic periods for better traffic management.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
Traffic-Congestion-Prediction/
│
├── traffic.csv
├── Traffic_Congestion_Prediction.ipynb
├── README.md
├── requirements.txt
└── assets/ (optional)
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Traffic-Congestion-Prediction.git
```

Move into the project directory:

```bash
cd Traffic-Congestion-Prediction
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
```

---

## 📈 Workflow

1. Load Traffic Dataset
2. Explore and Clean Data
3. Feature Engineering
4. Analyze Peak Traffic Hours
5. Perform Junction-wise Analysis
6. Label Congestion Levels
7. Train Random Forest Model
8. Evaluate Model Performance
9. Predict Traffic Congestion
10. Generate Dashboard Summary

---

## 🎯 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost & LightGBM Models
- Real-Time Traffic Prediction
- Traffic Forecasting using LSTM
- Streamlit Dashboard
- Flask/FastAPI Deployment
- Integration with Live Traffic APIs

---

## 👨‍💻 Author

**Abhijeet N G**

GitHub: https://github.com/your-username

---

## 📜 License

This project is intended for educational and learning purposes.