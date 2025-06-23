# 🛳️ Titanic Dataset - Data Cleaning & Preprocessing

---

## 📌 Objective

- Handle missing values
- Encode categorical variables
- Normalize/standardize numerical features
- Visualize and remove outliers

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.csv`

---

## 🔍 Steps Performed

### 1. Data Exploration
- Used `df.head()`, `df.info()`, `df.describe()`, and `df.isnull().sum()` to understand the data structure and missing values.

### 2. Handling Missing Values
- Filled missing `Age` values with median.
- Filled missing `Embarked` values with mode.
- Dropped the `Cabin` column due to excessive missing values.

### 3. Encoding Categorical Features
- Encoded `Sex` and `Embarked` columns using `LabelEncoder`.

### 4. Feature Scaling
- Standardized `Age` and `Fare` columns using `StandardScaler`.

### 5. Outlier Detection and Removal
- Visualized `Age` and `Fare` using boxplots.
- Removed outliers using the Interquartile Range (IQR) method.

---

## 📊 Final Output

- Cleaned dataset saved as `titanic_cleaned.csv`.
- Ready for ML model training.

---
