# Final Project: Network Intrusion Detection Using Machine Learning

## Course: CS6140 – Machine Learning (Fall 2024)

### Author: *Reena Sajad Hyder*  
### Presentation: [Final Project Presentation on Canva](https://www.canva.com/design/DAGZBte-KsM/msGp8Om2IdcQkFl9fA1qoA/edit?utm_content=DAGZBte-KsM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 📌 Objective

This project explores the application of machine learning to **network intrusion detection** using a labeled dataset of real-world packet captures. The primary objective is to build models that accurately identify potential threats within network traffic using statistical and behavioral patterns.

---

## 📁 Dataset

The dataset used is publicly available on Kaggle:  
🔗 [Network Intrusion Dataset on Kaggle](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)

It contains packet flow data segmented by day and time, including both normal and attack traffic. The flows are represented by numerical features such as packet lengths, inter-arrival times, and flags.

---

## 🧠 Approach

The project analyzes three distinct time periods from the dataset:
- **Tuesday Working Hours**
- **Thursday Working Hours Morning**
- **Friday Working Hours Afternoon**

Each notebook processes and models the data from one of these periods, allowing for temporal analysis of network behavior.

---

## 🔧 Methodology

### 1. Data Preprocessing
- Removed irrelevant or constant columns
- Handled missing values and encoded categorical variables
- Normalized numerical features using `StandardScaler`

### 2. Feature Selection
- Applied correlation analysis to remove redundant features
- Selected high-importance features based on tree-based models

### 3. Modeling Techniques
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- Isolation Forest (for anomaly detection)

### 4. Evaluation Metrics
- Accuracy
- Precision, Recall, and F1-Score
- Confusion Matrix
- ROC-AUC Curve (where applicable)

---

## 📂 Files Included

- `FinalProject-Tuesday_WorkingHours.ipynb`  
- `FinalProject-Thursday_WorkingHours_Morning.ipynb`  
- `FinalProject-Friday_WorkingHours_Afternoon.ipynb`  

---

## ✅ Summary

This project demonstrates how machine learning can be used to detect intrusions in network traffic by learning patterns from flow-based features. With robust preprocessing, feature selection, and ensemble modeling, we can build accurate and interpretable models that contribute to network security solutions.
