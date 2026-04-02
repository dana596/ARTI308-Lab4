# Data Quality Assessment & Preprocessing Lab

## 📌 Lab Objective

The purpose of this lab is to understand how to clean and preprocess data before analysis. This includes handling missing values, removing duplicates, calculating basic statistics, detecting outliers, and normalizing data.

---

## 📂 Dataset

A dataset (e.g., student performance data) was used. It contains both numerical and categorical values.

---

## ⚙️ Steps

### 1. Data Loading

* Loaded the dataset using Pandas
* Displayed first rows using `head()`

### 2. Data Understanding

* Checked data types using `info()`
* Viewed summary statistics using `describe()`

### 3. Data Cleaning

* Checked for missing values using `isnull()`
* Removed missing values
* Removed duplicate rows

### 4. Basic Statistics

Calculated:

* Mean
* Median
* Mode

### 5. Outliers Detection

* Used IQR method (Q1, Q3)
* Identified outliers
* Removed them

### 6. Normalization

* Applied Min-Max normalization
* Scaled values between 0 and 1

