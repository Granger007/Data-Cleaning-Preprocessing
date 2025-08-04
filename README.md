Data Cleaning & Preprocessing for Machine Learning
      This project demonstrates a complete data cleaning and preprocessing pipeline using Python. The goal is to transform raw, messy data into a clean, structured format ready for machine learning tasks.

Tools & Libraries Used:

 => Python

 => Pandas – Data manipulation

 => NumPy – Numerical operations

 => Matplotlib / Seaborn – Data visualization

 => Scikit-learn – Standardization, encoding

📁 Workflow Overview
1. Import Dataset
Load CSV data using pandas.read_csv()

2. Basic Exploration
Check shape, datatypes, and missing values

Display basic statistics using .info(), .describe(), .isnull().sum()

3. Handle Missing Values
Fill numerical columns with mean

Fill categorical columns with mode

No chained assignment (future-proof)

4. Encode Categorical Variables
Label encode object-type features using LabelEncoder

(Can switch to one-hot encoding for better generalization)

5. Standardize Numerical Features
Normalize all numerical columns using StandardScaler

6. Visualize Outliers
Use boxplots for each numerical feature

Plot all at once or one-by-one based on count

7. Remove Outliers
IQR method (Q1 - 1.5 * IQR, Q3 + 1.5 * IQR)

Loop through numeric columns and filter out extreme values


