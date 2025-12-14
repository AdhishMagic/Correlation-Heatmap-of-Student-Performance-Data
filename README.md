# 📊 Student Performance Correlation Analysis

This project explores the relationships between various student-related factors and academic performance using **correlation analysis** and **heatmap visualization**. The goal is to identify which factors are most strongly associated with student performance.

---

## 📌 Project Objective

To analyze how different attributes such as study hours, previous scores, sleep patterns, extracurricular activities, and practice habits correlate with the **Performance Index** of students.

---

## 📂 Dataset Description

The dataset consists of the following features:

| Column Name | Description |
|------------|-------------|
| Hours Studied | Number of hours spent studying |
| Previous Scores | Academic score from previous assessments |
| Extracurricular Activities | Participation status (Yes / No) |
| Sleep Hours | Average daily sleep duration |
| Sample Question Papers Practiced | Number of practice papers solved |
| Performance Index | Final performance score (target variable) |

---

## 🔄 Data Preprocessing Steps

1. Loaded the dataset into a pandas DataFrame  
2. Converted categorical values:
   - `Yes → 1`
   - `No → 0`
3. Selected numerical columns for correlation analysis  
4. Checked data consistency and structure  

---

## 📈 Exploratory Data Analysis

### Correlation Analysis
- Pearson correlation coefficient was used to measure linear relationships between variables.
- A **correlation matrix** was generated to compare each feature with others.

### Heatmap Visualization
- A heatmap was created to visually represent correlation strengths.
- Color intensity indicates the magnitude of correlation:
  - Darker colors → stronger correlation
  - Lighter colors → weaker correlation

---

## 🔍 Key Insights

- **Previous Scores** show a strong positive correlation with **Performance Index**
- **Hours Studied** and **Sample Question Papers Practiced** have moderate positive correlations
- **Sleep Hours** and **Extracurricular Activities** show weak or minimal correlation
- Correlation indicates association, not causation

