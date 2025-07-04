# 📊 Exploratory Data Analysis of Diabetes Patient Health Metrics

This project performs a comprehensive Exploratory Data Analysis (EDA) on a diabetes dataset to uncover patterns, correlations, and insights from various health-related indicators. It helps identify important features that can contribute to predicting diabetes.

---

## 📁 Dataset

- **File**: `diabetes.csv`
- **Source**: [Pima Indians Diabetes Dataset – Kaggle / UCI Machine Learning Repository]
- **Features Include**:
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`
  - `Outcome` (0 = Non-diabetic, 1 = Diabetic)

---

## 🎯 Objectives

- Understand the structure and distribution of the dataset
- Handle missing/null values if present
- Visualize feature distributions and relationships
- Explore correlations between health metrics
- Support future model-building efforts through visual insights

---

## 🛠️ Tools & Libraries

- **Python 3.11**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization

---

## 📈 Key EDA Steps

### ✅ 1. Dataset Overview
- View basic info with `.info()`, `.describe()`, `.shape`, `.columns`

### ✅ 2. Missing Value Analysis
- Checked for null/missing values using `data.isnull().sum()`

### ✅ 3. Univariate Visualizations
- `Histograms` for age, glucose, BMI
- `Box plots` to detect outliers (e.g., BMI)
- `Distribution plots` using Seaborn

### ✅ 4. Bivariate & Multivariate Visualizations
- `Scatterplots`: BMI vs Age, BloodPressure vs Glucose
- `Bar plots`: Aggregated views
- `Pairplot`: Overall variable relationships (colored by `Outcome`)
- `Correlation heatmap`: To identify strong linear associations

### ✅ 5. Custom Visualization
- `Pie chart`: Glucose levels grouped into Low, Normal, High ranges

---

## 🔍 Sample Visualizations

- 🔴 **Scatter Plot** – BMI vs Age  
- 🟩 **Histogram** – Glucose distribution  
- 🟦 **Box Plot** – BMI outlier detection  
- 🟨 **Correlation Heatmap** – All numerical features  
- 🟠 **Pairplot** – Colored by Outcome  
- 🟣 **Pie Chart** – Glucose level categories

---
