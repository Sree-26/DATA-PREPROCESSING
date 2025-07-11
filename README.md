# 🧹 Data Preprocessing Task – Diabetes Dataset (GFG)

This repository contains a Google Colab notebook where I performed data preprocessing on a **Diabetes dataset** obtained from **GeeksforGeeks (GFG)**. The goal of this task was to clean the data by handling missing values and normalizing numerical features using `StandardScaler` from Scikit-learn.

🔗 **Notebook**: [datapreprocessingtask.ipynb](https://github.com/Sree-26/DATA-PREPROCESSING/blob/main/datapreprocessingtask.ipynb)

---

## 📁 Files Included

- `datapreprocessingtask.ipynb` – The complete preprocessing notebook.

---

## 📊 Dataset Information

- **Source**: GeeksforGeeks  
- **Topic**: Diabetes prediction  
- **Format**: CSV  
- **Contents**: Includes features like glucose levels, blood pressure, BMI, etc.

---

## 🔧 Preprocessing Steps

1. **Loaded** the dataset using `pandas`
2. **Checked for missing values** and handled them appropriately
3. **Normalized** numeric features using:
   ```python
   from sklearn.preprocessing import StandardScaler
   scaler = StandardScaler()
   rescaledX = scaler.fit_transform(X)
