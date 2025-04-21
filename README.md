# Task-1

# Task 1 - Data Cleaning and Preprocessing 🧹

## 📌 Internship Task Objective
To clean and preprocess the **Customer Personality Analysis** dataset by addressing missing values, duplicates, inconsistent formats, and preparing the dataset for future analysis.

---

## 🧰 Tools Used
- Python 🐍
- Pandas Library 📊
- Jupyter Notebook 📓

---

## 📂 Dataset
- **Name**: Customer Personality Analysis
- **Source**: Kaggle ([link](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis))

---

## 🔍 Steps Performed

### 1. Data Inspection
- Loaded the dataset using `pandas.read_csv()`
- Used `.info()` and `.describe()` to understand structure and stats

### 2. Handling Missing Values
- Used `.isnull().sum()` to detect missing values
- Treated missing values by:
  - Filling with mean/median for numerical columns
  - Dropping rows/columns where appropriate

### 3. Removing Duplicates
- Used `.duplicated().sum()` to identify duplicates
- Removed them using `.drop_duplicates()`

### 4. Renaming Columns
- Cleaned and renamed columns: lowercase, underscores instead of spaces

### 5. Fixing Data Types
- Converted appropriate columns to:
  - `int` or `float` for numerical
  - `datetime` for dates using `pd.to_datetime()`

### 6. Standardizing Data
- Unified inconsistent category values (like gender, marital status)
- Ensured uniform formatting for categorical variables

---

## ✅ Final Output
- Cleaned dataset: `cleaned_customer_data.csv`
- Notebook: `Task 1 on Customer Personality Analysis.ipynb`

---

## 📌 Summary of Changes

| Change                       | Description |
|-----------------------------|-------------|
| Missing Values              | Filled using median/mean, dropped where necessary |
| Duplicates                  | Removed duplicate rows |
| Column Names                | Standardized column naming convention |
| Data Types                  | Converted data types (e.g., date, age) |
| Categorical Standardization | Gender and marital status normalized |

---

## 💬 Interview Prep Questions Covered

- What are missing values and how do you handle them?
- How do you treat duplicate records?
- Difference between `dropna()` and `fillna()` in Pandas?
- What is outlier treatment and why is it important?
- How do you standardize data?
- How do you fix inconsistent data formats (e.g., dates)?
- What are common challenges in data cleaning?
- How can you assess data quality?

---

## 🚀 Learnings
- Gained practical experience in data cleaning and preprocessing
- Learned how to make a dataset analysis-ready
- Improved skills in Pandas and real-world data handling

---

## 🔗 Submission Link
[GitHub Repository Link Here]

