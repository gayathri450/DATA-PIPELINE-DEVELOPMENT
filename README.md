﻿# DATA-PIPELINE_DEVELOPMENT
📝 Task Description: Data Pipeline Development (CODTECH Internship - Task 1)
✅ Objective:
To design and implement a data pipeline that automates the ETL (Extract, Transform, Load) process using tools like Pandas and Scikit-learn. The pipeline should handle data preprocessing, transformation, and saving the processed output for further analysis or model building.

📂 Dataset Used:
The dataset (data.csv) consists of information including:

Category: A categorical variable indicating the type or class of a product.

Price: Numerical data representing the price of the product.

UnitsSold: Numerical data representing the quantity of units sold.

🔧 Steps Performed in the Pipeline:
Importing Libraries:

Utilized pandas for data handling.

Used StandardScaler from sklearn.preprocessing for feature scaling.

Data Loading:

Read the raw data from data.csv.

Data Cleaning:

Removed rows with missing values using dropna() to ensure data consistency.

Data Transformation:

Converted the categorical Category column to numerical format using label encoding (cat.codes).

Standardized numerical features (Price and UnitsSold) to bring them to a similar scale using StandardScaler.

Data Exporting:

Saved the final cleaned and transformed dataset into a new file processed_data.csv.

🎯 Outcome:
The pipeline ensures that the data is ready for modeling or analytics by:

Handling missing values.

Encoding categorical variables.

Normalizing numerical features.

Saving a clean and structured dataset.
