Exploratory Data Analysis (EDA) – Chronic Kidney Disease Dataset

📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Chronic Kidney Disease (CKD) dataset to understand the underlying structure of the data, identify important patterns, handle missing values, and analyze key medical attributes related to kidney health. The insights derived from this analysis can support early diagnosis and serve as a foundation for machine learning models.

🎯 Objectives

Understand the distribution of clinical features

Identify missing and inconsistent values

Analyze relationships between medical parameters

Detect trends and patterns associated with chronic kidney disease

Prepare data for further predictive modeling

🧬 Dataset Description

The dataset contains patient medical records with attributes such as:

Age

Blood Pressure

Specific Gravity

Albumin

Sugar

Blood Glucose Random

Blood Urea

Serum Creatinine

Hemoglobin

Packed Cell Volume

White Blood Cell Count

Red Blood Cell Count

Hypertension, Diabetes Mellitus, Anemia, etc.

Target variable: Chronic Kidney Disease (CKD / Not CKD)

🛠️ Technologies Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Jupyter Notebook

📊 EDA Steps Performed

Data loading and inspection

Handling missing values

Data type corrections

Statistical summary of features

Univariate analysis (histograms, count plots)

Bivariate analysis (correlation heatmaps, comparisons)

Class distribution analysis

🔍 Key Insights

Several medical attributes contain missing values that require preprocessing

Certain features like serum creatinine, hemoglobin, and blood urea show strong correlation with CKD

CKD patients exhibit noticeable differences in blood-related parameters

📁 Project Structure
├── EDA_chronic_data.ipynb
├── README.md

🚀 Future Scope

Feature engineering and selection

Building machine learning models for CKD prediction

Model evaluation and optimization
