
# 📊 EDA and Feature Engineering on Student Performance Dataset

This project performs Exploratory Data Analysis (EDA) and feature engineering on a student performance dataset to better understand the relationships between demographic and academic features.

## Dataset Overview

- **File Name**: StudentsPerformance.csv
- **Source**: Public dataset (or custom uploaded)
- **Features**:
  - `gender`: Male or Female
  - `race/ethnicity`: Group classification
  - `parental level of education`
  - `lunch`: Standard or free/reduced
  - `test preparation course`: Completed or none
  - `math score`, `reading score`, `writing score`

## Project Objectives

- Perform descriptive statistical analysis
- Visualize distributions and relationships among features
- Handle missing values and data types
- Engineer new features such as:
  - `total_score`, `average_score`
  - Performance categories (e.g., High/Medium/Low)
- Prepare dataset for further machine learning tasks

## EDA Highlights

- Distribution plots for math, reading, and writing scores
- Count plots for categorical variables
- Correlation heatmap
- Boxplots and violin plots for performance by gender, lunch, etc.
- Grouped means and performance breakdown

## Feature Engineering Performed
- Created:
  - `total_score` = sum of all scores
  - `average_score` = total / 3
  - `performance_level` = categorized average scores
- Encoded categorical variables
- Removed/treated outliers
- 
## Files in Repository
student-performance-eda
- data/StudentsPerformance.csv
- EDA STUDENT PERFORMANCE.ipynb
- README.md

