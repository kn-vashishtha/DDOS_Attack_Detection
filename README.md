🛡️ DDoS Attack Detection using Machine Learning

This project presents a robust machine learning and deep learning-based system to detect Distributed Denial of Service (DDoS) attacks in network traffic data. Leveraging multiple algorithms, it identifies malicious patterns with high precision and recall, making it suitable for real-world intrusion detection use cases.

## 🔍 Project Overview

- Developed a machine learning-based system to detect DDoS attacks using a dataset of **4.5 lakh entries**, split into **60% testing and 40% training**.
- Applied advanced **data preprocessing**, **feature engineering**, and techniques to address **class imbalance**.
- Trained and compared multiple models including:
  - 🔁 **Bi-directional LSTM (BiLSTM)**
  - 🌲 **Random Forest Classifier**
  - 🧠 **Feedforward Neural Network (FFNN)**
  - ➕ **Logistic Regression**

## 📊 Dataset

The project uses two CSV files:

- 🔹 **Normal Traffic Dataset**  
  [Download from Google Drive](https://drive.google.com/file/d/1jVNPZb50zhlaIlfd2ef6KUeLdtYYCR5i/view?usp=sharing)

- 🔹 **DDoS Attack Traffic Dataset**  
  [Download from Google Drive](https://drive.google.com/file/d/16Osj3lbds0ibQNuClMAX91f0YcQrzXSV/view?usp=sharing)

> ⚠️ These files are not included in the repository due to size constraints. Please download and place them in the `data/` directory.

## 📁 Project Structure

.
├── data/
│ ├── normal.csv
│ └── attack.csv
├── ddos_detection_model.ipynb
├── requirements.txt
└── README.md

## ⚙️ Features

- Data preprocessing: handling missing values, encoding, normalization
- Feature selection and reduction
- Class balancing techniques (e.g., under-sampling, SMOTE if applicable)
- Model training, evaluation, and comparison
- Metrics visualization: accuracy, precision, recall, confusion matrix

## 🧠 Algorithms Used

| Algorithm                | Type            |
|--------------------------|------------------|
| Bi-directional LSTM      | Deep Learning    |
| Random Forest Classifier | Ensemble Learning|
| Feedforward Neural Net   | Deep Learning    |
| Logistic Regression      | Traditional ML   |

## 📈 Results

The best performance was achieved using **BiLSTM**:

| Metric     | Value    |
|------------|----------|
| Accuracy   | 98.12%   |
| Precision  | 96.81%   |
| Recall     | 99.51%   |

> ✅ These results indicate strong detection performance and low false negatives — crucial for DDoS prevention systems.
## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/kn-vashishtha/DDOS_Attack_Detection.git
   cd DDOS_Attack_Detection
2. Install the required dependencies:
    pip install -r requirements.txt
3. Place the downloaded datasets inside the data/ folder:
    /data/normal.csv
    /data/attack.csv
4. Launch the notebook:
    jupyter notebook fraud_detection_model.ipynb
