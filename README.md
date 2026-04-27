# student-data-transformation-pandas
This project focuses on cleaning and preprocessing a real-world styled student dataset using Python and Pandas.

# 🎓 Student Data Cleaning & Preprocessing Project

## 📌 Overview
This project demonstrates real-world data cleaning and preprocessing using Python (Pandas).  
The dataset represents student information including marks, gender, city, and email.

---

## 📊 Dataset Features
- student_id
- name
- age
- gender
- marks
- email
- city

---

## ❌ Problems in Raw Dataset
The original dataset had several issues:

- Missing values (`NaN`, `absent`)
- Incorrect data types (`"twenty"` instead of numeric)
- Duplicate records (same student repeated)
- Invalid emails (`manish@gmail` missing domain)
- Inconsistent formatting

---

## 🧹 Data Cleaning Steps

### 1. Handling Missing Values
- Replaced `NaN` and `absent` in marks
- Filled missing city values
- Removed or imputed null entries

### 2. Data Type Conversion
- Converted age column to numeric
- Handled non-numeric values

### 3. Duplicate Removal
- Removed repeated student entries

### 4. String Cleaning
- Standardized names and gender values
- Fixed inconsistent text formatting

### 5. Email Validation
- Identified and handled invalid email formats

### 6. Feature Engineering
- Calculated:
  - `male_avg`
  - `female_avg`
  - `avg_male`

---

## ✅ Final Output
Clean dataset with:
- No missing values
- Correct data types
- Consistent formatting
- Additional analytical columns

---

## 📈 Key Insights
- Average marks of male students: **74.0**
- Average marks of female students: **88.5**
- Female students performed better on average

---

## 🛠️ Technologies Used
- Python
- Pandas
- Jupyter Notebook

---

## 🚀 How to Run

```bash
pip install pandas
Open Jupyter Notebook and run:

import pandas as pd

📦 student-data-cleaning
 ┣ 📜 student_dataset.csv        # Raw dataset
 ┣ 📜 cleaned_dataset.csv        # Cleaned dataset
 ┣ 📜 student_dataset.ipynb      # Notebook with cleaning steps
 ┗ 📜 README.md
