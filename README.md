# Simulated Machine Learning-Based Intrusion Detection System for Network Security

## 📌 Project Overview  
This project focuses on developing a **Machine Learning-based Intrusion Detection System (IDS)** to enhance network security. The system analyzes network traffic patterns to detect malicious activities using various ML models. A **web interface** has been developed to allow users to interact with the IDS seamlessly.  

## 📂 Dataset  
The **KDD dataset** is used for training and evaluation. This dataset contains labeled network traffic data, including both normal and attack patterns, making it a standard benchmark for intrusion detection research.  

## 🛠️ Machine Learning Models Tried  
Multiple machine learning models were trained and evaluated to find the most effective approach:  

- ✅ **Decision Tree (Final Model)**  
- 🔹 k-Nearest Neighbors (KNN)  
- 🔹 k-Means Clustering  
- 🔹 Random Forest  
- 🔹 Support Vector Machine (SVM)  

After evaluation, **Decision Tree** was selected as the final model due to its superior performance in detecting network intrusions.  

## 🖥️ Web Interface  
A **web-based interface** has been developed to make the system user-friendly. The interface allows users to:  
- Upload network traffic data for analysis  
- View predictions on whether the traffic is normal or an attack  
- Access model performance metrics  

## 📊 Model Performance  
The project includes performance evaluation metrics, including **confusion matrices** for all tested models. These help in understanding how well each model performed in distinguishing between normal and malicious network traffic.  

## 🚀 How to Use  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/KamakshiChavva/intrusion-detection-system.git
