This project demonstrates a complete data cleaning and preprocessing pipeline using Python. The goal is to transform raw, messy data into a clean, structured format ready for machine learning tasks.

🔧 Tools & Libraries Used:

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib / Seaborn – Data visualization

Scikit-learn – Standardization, encoding

📁 Workflow Overview

✅ Import Dataset

Load CSV data using pandas.read_csv()

✅ Basic Exploration

Check shape, datatypes, and missing values

Display basic statistics using .info(), .describe(), .isnull().sum()

✅ Handle Missing Values

Fill numerical columns with mean

Fill categorical columns with mode

Avoid chained assignment for future-proof compatibility

✅ Encode Categorical Variables

Label encode object-type features using LabelEncoder

(Can switch to one-hot encoding for better generalization)

✅ Standardize Numerical Features

Normalize all numerical columns using StandardScaler

✅ Visualize Outliers

Use boxplots for each numerical feature

Plot all at once or one-by-one based on feature count

✅ Remove Outliers

Use IQR method: Q1 - 1.5 * IQR to Q3 + 1.5 * IQR

Loop through numeric columns and filter out extreme values
