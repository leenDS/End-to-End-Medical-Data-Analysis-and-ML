# End-to-End-Medical-Data-Analysis-and-ML

# Medical Data Analysis & Diabetes Prediction Pipeline

## 📌 Project Overview
This project focuses on performing an in-depth **Exploratory Data Analysis (EDA)** and building a predictive model for diabetes detection. The core value of this repository lies in the robust data preprocessing phase, where I addressed common real-world data challenges such as high class imbalance, outliers, and feature redundancy.

## 🚀 Key Technical Challenges Addressed
- **Class Imbalance Handling:** The dataset was significantly biased towards non-diabetic cases. I implemented **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the training data, ensuring the model doesn't just "guess" the majority class but actually learns the patterns of diabetic patients.
- **Advanced EDA:** Conducted comprehensive statistical analysis using Boxplots for outlier detection and Heatmaps for correlation analysis to identify the most impactful health indicators (HbA1c and Blood Glucose levels).
- **Data Integrity:** Performed rigorous data cleaning, including duplicate removal and handling missing/informational-only features to prevent model leakage and noise.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE)
- **Visualization:** Seaborn, Matplotlib

## 📊 Modeling & Evaluation
I evaluated multiple classifiers to find the best balance between Precision and Recall (F1-Score), which is critical in medical diagnostics:
- **Logistic Regression** (Baseline)
- **Random Forest Classifier**
- **K-Nearest Neighbors**

**Final Result:** The optimized Random Forest model achieved a high **F1-Score**, demonstrating its reliability in identifying true positive cases compared to standard accuracy metrics.


## ⚙️ Setup
1. Clone the repo:
   ```bash
   git clone [https://github.com/LeenDS/End-to-End-Medical-Data-Analysis.git](https://github.com/LeenDS/End-to-End-Medical-Data-Analysis.git)
