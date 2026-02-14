# IDEAS-TIH-Coffee-Sales-Analysis
Spring Internship 2026 Project: Coffee Sales Dataset Cleaning, Analysis, and Revenue Prediction using Linear Regression.
## 📌 Project Overview

This project is based on a Coffee Sales dataset and focuses on:

- Cleaning and exploring coffee shop transaction data  
- Performing basic exploratory data analysis (EDA)  
- Building a simple Linear Regression model to predict sales amount (`money`)  

The notebook demonstrates how coffee sales vary across different coffee types, weekdays, and time patterns.

---

## 📂 Dataset Description

The dataset contains coffee shop sales transactions with the following key columns:

- `hour_of_day` → Hour of the day when purchase was made  
- `cash_type` → Payment method (card/cash)  
- `money` → Sales amount (target variable)  
- `coffee_name` → Type of coffee purchased  
- `Time_of_Day` → Morning / Afternoon / Night  
- `Weekday` → Day of the week (Mon, Tue, Fri, etc.)  
- `Month_name` → Month of transaction  
- `Date` → Transaction date  
- `Time` → Transaction time  

---

## ⚙️ Steps Performed

### 1. Data Loading
- Imported the dataset using Pandas  
- Displayed dataset shape and initial rows  

### 2. Data Cleaning
- Checked duplicate rows  
- Checked missing values  
- Converted `Date` column into datetime format  
- Extracted `Month` and `Year` from the date  

---

## 📊 Exploratory Data Analysis (EDA)

The following insights were generated:

- Average sales by year  
- Maximum sales by month  
- Total revenue by coffee type  
- Mean sales by time of day  
- Unique coffee varieties available  

Example analysis:

- Which coffee type earns the most revenue?
- Which time of day has the highest average sales?

---

## 🤖 Machine Learning Model

A **Linear Regression model** was trained to predict coffee sales amount (`money`) based on:

- `hour_of_day`
- `coffee_name`
- `Weekday`

Categorical features were converted into numerical values using one-hot encoding (`pd.get_dummies()`).

---

## 📌 Model Evaluation

The model performance was evaluated using:

- **Mean Squared Error (MSE)**

---

## 🔍 Sample Prediction

The notebook also demonstrates prediction for a new input example:

- Hour: 9 AM  
- Coffee: Cappuccino  
- Weekday: Friday  

The model predicts the expected sales amount for the given transaction.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 🚀 How to Run This Project

1. Clone the repository:

```bash
git clone https://github.com/bipashasaha2022-creatorcreate/IDEAS-TIH-Coffee-Sales-Analysis.git
2. Open the Jupyter Notebook

02-Exploratory_data_analysis_with_sales_data_Spring_2026.ipynb
3.Install required libraries
pip install pandas numpy scikit-learn


##Conclusion
This project shows how basic data analysis and a simple regression model can help understand coffee sales patterns and predict transaction revenue based on time and coffee type.

##👩‍💻Author
Bipasha Saha
IDEAS-TIH Spring Internship Project (2026)
IDEAS-TIH-Coffee-Sales-Analysis
