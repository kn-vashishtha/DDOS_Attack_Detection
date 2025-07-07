# 🛡️ DDoS Attack Detection using Machine Learning

This project focuses on building a robust **fraud detection model** capable of identifying malicious patterns in network traffic or financial transactions using **machine learning algorithms**. It is inspired by credit card fraud detection and adapted to detect **DDoS-style anomalies** in structured datasets.

## 🔍 Project Overview

- Developed a **fraud detection system** using:
  - **Bi-Directional LSTM**
  - **Random Forest Classifier**
  - **Logistic Regression**
  - **Feed Forward Neural Network**
- Achieved:
  - ✅ **99% Accuracy**
  - ✅ **91.5% Precision**
  - ✅ **79.2% Recall**
- Applied:
  - **Feature engineering**
  - **Data preprocessing**
  - Techniques to handle **imbalanced datasets**, significantly reducing false positives.

## 📊 Dataset

This project uses two separate CSV datasets:

- 🔹 **Normal Traffic Dataset**  
  [Download from Google Drive](https://drive.google.com/file/d/1jVNPZb50zhlaIlfd2ef6KUeLdtYYCR5i/view?usp=sharing)

- 🔹 **DDoS Attack Traffic Dataset**  
  [Download from Google Drive](https://drive.google.com/file/d/16Osj3lbds0ibQNuClMAX91f0YcQrzXSV/view?usp=sharing)

> ⚠️ These datasets are not stored in the repository due to size limits. Please download them manually and place them in the `/data/` folder.

## 📁 Project Structure

.
├── data/
│ ├── normal.csv
│ └── attack.csv
├── fraud_detection_model.ipynb
├── requirements.txt
└── README.md


## ⚙️ Features

- Data loading and preprocessing (handling missing values, encoding)
- Feature selection & dimensionality reduction (if applicable)
- Model training and evaluation with:
  - Confusion matrix
  - Accuracy, precision, recall scores
- Visualizations of data distribution and results

## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/your-username/ddos-fraud-detection.git
   cd ddos-fraud-detection
2. Install the required dependencies:
    pip install -r requirements.txt
3. Place the downloaded datasets inside the data/ folder:
    /data/normal.csv
    /data/attack.csv
4. Launch the notebook:
    jupyter notebook fraud_detection_model.ipynb
