# 📊Analysis-of-NHANES-Body-Measurements

## Overview

This project analyzes anthropometric data (body measurements) for adult males and females using statistical and visualization techniques in Python. The focus is on understanding the relationships between weight, height, waist, hip, and BMI. The dataset is standardized using Z-score normalization to compare features on a common scale, and visual insights are drawn using plots.

---

## 🎯 Objectives

- Clean and preprocess male and female datasets.
- Standardize features using Z-score normalization.
- Visualize feature distributions and correlations using boxplots and pairplots.
- Identify and analyze individuals with extreme BMI values.
- Derive insights from relationships among features.

---


---

## 📊 Methodology

### 1. **Data Preprocessing**
- Missing values were removed to ensure clean data for analysis.
- Separate subsets were created for males and females.

### 2. **Z-Score Standardization**
- Standardized all measurements to enable fair comparison.
- Z-score = (value - mean) / standard deviation

### 3. **Visualizations**
- **Boxplot**: Showed weight distribution by gender, highlighting central tendency and outliers.
- **Pairplots**: Illustrated pairwise relationships among weight, height, waist, hip, and BMI.
  - Males and females showed strong correlations between weight, waist, hip, and BMI.

### 4. **Extreme BMI Case Study**
- Identified 5 individuals with the **lowest BMI** and 5 with the **highest BMI** from the female dataset.
- Analyzed their standardized body measurements.

---

## 📌 Results Summary

- **BMI** is positively correlated with **waist** and **hip** circumference.
- **Weight** plays a major role in BMI, with **height** influencing the scale.
- **Lowest BMI individuals** tend to have lower weight and larger height.
- **Highest BMI individuals** show high weight and waist/hip measures, often with shorter height.
- Standardization helped highlight outliers and patterns clearly.

---



## 🧪 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ⚙️ How to Run

1. Clone the repo:

```bash
git clone https://github.com/your-username/body-measurements-analysis.git
cd body-measurements-analysis

