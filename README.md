# AI-ML
Collection of AI/ML projects from my Data Science internship at Main Crafts Technology. Includes EDA, data visualization, and ML models using Python, Pandas, Matplotlib, Seaborn on datasets like Student Performance, Iris, and Titanic.
This repository contains my Data Science & Machine Learning projects completed during my internship at *Main Crafts Technology*.

## 📊 Projects

 📊 Task 1: Student Performance Data Analysis

### *Overview*
End-to-end exploratory data analysis on the UCI Student Performance Dataset to identify key factors influencing final grades of secondary school students in Portugal.

### *Dataset*
- *Source*: UCI Machine Learning Repository - Student Performance Dataset
- *File Used*: student-mat.csv - Math course performance
- *Size*: 395 students × 33 features
- *Target Variable*: G3 - Final grade from 0 to 20

### *Objective*
Perform data cleaning, EDA, and statistical analysis to answer: What factors most impact student performance?

### *Workflow*
1. *Data Loading*: Imported CSV with sep=';' delimiter handling
2. *Data Cleaning*: Checked for nulls, duplicates. Verified data types
3. *Exploratory Data Analysis*: 
   - Univariate: Grade distributions, study time, absences
   - Bivariate: Study time vs G3, Gender vs G3, Alcohol vs G3
4. *Categorical Encoding*: Converted sex, address, famsize to numeric using pd.get_dummies(dtype=int)
5. *Visualization*: Histograms, boxplots, scatter plots, correlation heatmap
6. *Key Insights*: Documented findings with markdown explanations

### *Key Findings*
- Average final grade G3: 10.42/20
- Weak positive correlation between study time and G3: 0.10
- Students with family educational support performed better on average
- High absences generally correlated with lower grades

### *Tech Stack*
Python Pandas NumPy Matplotlib Seaborn Jupyter Notebook
