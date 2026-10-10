# Data Cleaning and Preprocessing Project
## 📌 Project Overview
This project showcases advanced data cleaning and preprocessing techniques using Pandas and Scikit-learn, tailored for a marketing customer dataset. It is part of a larger data science workflow focused on transforming raw customer data into a machine learning-ready format.

## 📂 Dataset Information
The dataset consists of customer demographics and purchasing behavior, including:

Demographics: year_birth, education, marital_status, income

Purchase History: mntwines, mntfruits, mntmeatproducts, etc.

Web and Store Interaction Metrics

Campaign Responses and Complaints

## 🔧 Key Tasks Performed
## ✅ Data Cleaning
Standardized column names to lowercase_snake_case

Converted dt_customer to datetime format

Converted education and marital_status to categorical types

Handled missing values 

## ✅ Feature Engineering
Created a new column: customer_days (days since enrollment)

Dropped non-informative columns: id, dt_customer, z_costcontact, z_revenue

## ✅ Export
Exported the final cleaned and transformed dataset to: processed_data.csv

## 🧪 Libraries Used
pandas

numpy
