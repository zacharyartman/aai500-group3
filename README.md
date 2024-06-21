# AAI 500 Final Team Project

**Authors:** Zach Artman, Olga Pospelova, Narendra Fadnavis  
**Date:** 06/02/2024

## Project Title
Obesity Level Estimation Using Machine Learning

## Installation
To use this project, follow these steps:
1. Clone the repository.
2. Ensure you have Python installed. It is reccomended that you use the Anaconda version of Python so that you have the required libraries (mentioned below)
3. Run the Jupyter Notebook or the script to execute the project.

## Project Intro/Objective
The main purpose of this project is to estimate obesity levels based on eating habits and other physical conditions. By leveraging machine learning techniques, the project aims to provide insights into how different factors contribute to obesity, potentially aiding in public health interventions and personal health management.

## Partner(s)/Contributor(s)
- Zach Artman
- Olga Pospelova
- Narendra Fadnavis

## Methods Used
- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Machine Learning (Random Forest Classifier)
- Data Visualization

## Technologies
- Python
- pandas
- scikit-learn
- seaborn
- matplotlib

## Project Description
This project involves analyzing a dataset of various physical and dietary factors to predict obesity levels. The dataset includes variables such as gender, age, height, weight, family history with overweight, and more. After cleaning and preprocessing the data, we used exploratory data analysis to understand relationships between variables. Finally, a Random Forest Classifier was employed to predict obesity levels with high accuracy.

### Data Cleaning and Preparation
The dataset was cleaned and relevant columns were renamed for clarity. Categorical variables were encoded using LabelEncoder.

### Exploratory Data Analysis
- Correlation heatmaps and various plots were used to visualize relationships.
- Distribution plots for obesity levels and boxplots for age and weight against obesity levels were created.

### Model Selection
A Random Forest Classifier was chosen for its accuracy and ability to handle large datasets with many features. The model achieved an accuracy score of 94%.

### Key Findings
- Weight and height are significant predictors of obesity levels.
- Family history with overweight and eating habits also play crucial roles.
