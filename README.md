# Unified Payment Interface (UPI) Fraud Detection using Feed Forward Neural Network (FNN)

🚀 This project focuses on detecting fraudulent UPI transactions using a **Feed Forward Neural Network (FNN)**.  
The model is designed to classify transactions as **fraudulent** or **genuine** based on key behavioral and transactional features.

## 📌 Features Used
- Transaction Amount  
- Transaction Category & Type  
- Latitude & Longitude  
- Average Transaction Amount  
- Unusual Location / Unusual Amount  
- New Device Detection  
- Failed Login Attempts  

## ⚙️ Tech Stack
- Python, TensorFlow/Keras  
- Pandas, NumPy, Matplotlib  
- Scikit-learn  

## 📊 Workflow
1. Data Preprocessing & Feature Engineering  
2. Splitting dataset into Train/Test  
3. Building FNN model for classification  
4. Model Training & Hyperparameter tuning  
5. Evaluation using accuracy, precision, recall, and confusion matrix  

## 📈 Results
- Achieved reliable classification between fraudulent and genuine transactions  
- Visualized fraud detection performance with confusion matrix & accuracy curves  

## ▶️ How to Run
```bash
git clone https://github.com/vineelach7/-Unified-Payment-Interface-Fraud-Detection-Using-Feed-Forward-Neural-Network.git
cd UPI-Fraud-Detection-FNN
pip install -r requirements.txt
python src/train.py
