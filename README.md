# Human-Activity-Recognition-Model


## 📌 Overview
This project uses deep learning and machine learning models to classify human activities based on accelerometer and gyroscope sensor data from the UCI HAR dataset. The models implemented include:

- **Deep Learning**: LSTM & 1D CNN trained on raw sensor data
- **Machine Learning**: Random Forest, SVM, and Logistic Regression trained on TSFEL-extracted features
- **Comparison**: Performance of ML models trained on TSFEL-extracted features vs. author-provided features

## 📂 Dataset
- **Source**: [UCI Human Activity Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
- **Data**: Inertial sensor data (accelerometer & gyroscope) from a smartphone worn by subjects performing activities

## ⚡ Features
- Train **LSTM & CNN** on raw accelerometer & gyroscope data
- Extract time-series features using **TSFEL** and train ML models (RF, SVM, LR)
- Compare models trained on **TSFEL-extracted** vs. **author-provided** features
- **User Input Feature**: Predict activity based on user-entered sensor data
- **Visualization**: Accuracy plots for all models

## 🛠 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/HAR-DeepLearning-ML.git
cd HAR-DeepLearning-ML

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Usage
1. **Train models:**
```bash
python har_modeling.py
```
2. **Predict activity based on user input:**
   - Run the script and enter 561 space-separated sensor values.
   - The model will predict the activity.

## 📊 Model Performance Comparison
| Model              | Accuracy |
|-------------------|----------|
| LSTM              | 80%      |
| CNN               | 96%      |
| Random Forest     | 84%      |
| SVM               | 42%      |
| Logistic Regression | 73%      |

## 🖼️ Visualizations
- **Training vs. Validation Accuracy** (LSTM & CNN)
- **Machine Learning Model Accuracy Comparison**
- **Overall Model Comparison**

## 🎓 Acknowledgments
- UCI HAR Dataset authors
- TSFEL library developers


