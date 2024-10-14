# Employee Dataset Preprocessing

# Overview:
____
The goal of this project is to design and implement a robust data preprocessing system that addresses challenges such as:

* Missing values
* Outliers
* Inconsistent formatting
* Categorical variable encoding
* By performing effective preprocessing, we aim to enhance the data quality for further machine learning analysis.

# Dataset Description
____
The dataset contains the following columns:

**Company Name:** Name of the company.

**Employee Age:** Age of the employee.

**Employee Salary:** Employee's salary.

**Place:** The city where the employee works.

**Country:** Country where the employee works.

**Gender:** Employee's Gender.

# Preprocessing Steps
____
**1. Exploratory Data Analysis (EDA)**
* Examined the dataset to list down the unique values in each feature and calculated their lengths.
* Renamed the columns for better readability.
 
**2. Handling Missing and Inappropriate Values**
* Replaced 0 values in the Employee Age column with NaN values.
* Filled missing values in Employee Age and Employee Salary columns using the mean value of the respective columns.
* Replaced missing values in the Company and Place columns with mode value.
  
**3. Removing Duplicate Rows**
*Identified and removed duplicate rows to ensure data quality.

**4. Handling Outliers**
Used visualizations such as box plots to identify outliers in numerical columns (e.g., salary, age).
Treated the outliers using IQR method as needed.
