# Fraud Detection Using Machine Learning

## 📌 Project Overview
This project focuses on building a **fraud detection model** using machine learning. Fraudulent transactions are rare but very costly. The goal is to detect such cases effectively despite the **class imbalance** in the dataset.

## 📂 Dataset
The dataset contains information on financial transactions with features such as:
- `type` – type of transaction (TRANSFER, CASH_OUT, etc.)
- `amount` – transaction amount
- `oldbalanceOrg` – balance before the transaction
- `newbalanceOrig` – balance after the transaction
- `oldbalanceDest` – receiver’s balance before the transaction
- `newbalanceDest` – receiver’s balance after the transaction
- `isFraud` – target column (1 = Fraud, 0 = Genuine)

## ⚙️ Tools & Libraries
- **Python** → main programming language  
- **Pandas** → data cleaning & preprocessing  
- **NumPy** → numerical computations  
- **Matplotlib/Seaborn** → data visualization  
- **Scikit-learn** → machine learning models & evaluation  

## 🛠️ Steps Performed
1. **Data Cleaning**  
   - Removed irrelevant columns (`nameOrig`, `nameDest`)  
   - Handled class imbalance problem  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized transaction types and fraud distribution  
   - Checked correlation between features  

3. **Feature Selection**  
   - Dropped unnecessary columns  
   - Defined features (`X`) and target (`y`)  

4. **Model Building**  
   - Split dataset into training and testing sets  
   - Trained models using Scikit-learn  

5. **Evaluation**  
   - Measured performance using **accuracy, precision, recall, and F1-score**  
   - Observed how models handle imbalanced data  

## 📊 Results
- Model successfully identifies fraudulent transactions better than random guessing  
- Highlights the challenge of dealing with **imbalanced data** in real-world fraud detection  

## 🚀 Key Learnings
- Handling imbalanced datasets is crucial in fraud detection  
- Feature selection improves accuracy and reduces overfitting  
- Evaluation metrics beyond accuracy (precision/recall) are important  

## 🔗 Repository Link
This repository contains:  
- Jupyter Notebook with full code  
- Dataset (or dataset link)  
- Results and visualizations  

---
👩‍💻 **Created by:** Soni N  
## Extended Description
- Performed exploratory data analysis (EDA) to understand transaction patterns.
- Engineered features like transaction ratios and amount differences for better model performance.
- Handled missing values and scaled features using StandardScaler.
- Logistic Regression achieved 98% accuracy on test set; confusion matrix shows minimal false positives.
- Future improvements: explore Random Forest, XGBoost, and deploy as a real-time fraud detection API.
# fraud-detection
Fraud Detection ML project using Python
