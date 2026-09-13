# 🔧 Feature Engineering & Data Encoding with Python

This repository contains my practical learning and implementation of **Feature Engineering** and **Data Encoding** techniques as part of my Data Science learning journey.

The main goal was to understand how raw data can be transformed, cleaned, and prepared before being used for Machine Learning models.

---

## 📚 Topics Covered

### 🔧 Feature Engineering

- Handling Missing Values
- Handling Outliers
- IQR (Interquartile Range)
- Upsampling
- Downsampling
- SMOTE (Synthetic Minority Oversampling Technique)

### 🔢 Data Encoding

- Label Encoding
- One-Hot Encoding
- Ordinal Encoding
- Target-Guided Encoding

---

# 🔧 Feature Engineering

Feature Engineering is an important part of the Machine Learning workflow. It involves preparing and transforming data so that it can be used effectively by Machine Learning algorithms.

## 🧩 Handling Missing Values

In real-world datasets, missing values are common.

In this notebook, I practised:

- Identifying missing values
- Checking the number of missing values
- Understanding the impact of missing data
- Exploring different approaches for handling missing values

---

## 📊 Handling Outliers

I explored how to identify potential outliers using the **IQR (Interquartile Range)** method.

### Concepts Covered

- Minimum
- Q1 (First Quartile)
- Median
- Q3 (Third Quartile)
- Maximum
- IQR
- Lower Fence
- Upper Fence

### Formula

```text
IQR = Q3 - Q1

Lower Fence = Q1 - 1.5 × IQR

Upper Fence = Q3 + 1.5 × IQR
