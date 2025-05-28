
# Task 1 – Data Cleaning and Preprocessing

## 🎯 Objective
Clean and preprocess a raw dataset by handling missing values, duplicates, inconsistent formats, and column issues to prepare the data for analysis.

---

## 📂 Dataset
- **Name**: marketing_campaign.csv  
- **Source**: [Kaggle - Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
- **Format**: Tab-separated (.csv)

---

## ⚙️ Tools & Environment
- Python 3 (Pandas, NumPy)
- Google Colab

---

## 🔍 Data Cleaning Steps Performed

1. **Loaded** the dataset using the tab delimiter.
2. **Renamed** all columns to lowercase and replaced spaces with underscores.
3. **Handled missing values** in the `income` column by filling with the median.
4. **Removed duplicate rows** using `drop_duplicates()`.
5. **Converted** the `dt_customer` column to datetime format.
6. **Created new column** `age` from `year_birth` using: `age = 2025 - year_birth`.
7. **Standardized text columns** by converting them to lowercase and stripping spaces.
8. **Saved** the cleaned dataset as `cleaned_marketing_campaign.csv`.

---

## 📁 Output Files
- `cleaned_marketing_campaign.csv` – Final cleaned dataset
- `Task1_DataCleaning.ipynb` – Colab notebook with all code
- `README.md` – This summary file

---

## 🧠 Learning Outcomes
- Practiced handling missing, duplicate, and inconsistent data.
- Understood data types and text standardization.
- Gained experience preparing real-world datasets for analysis.


