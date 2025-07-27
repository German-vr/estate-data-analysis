# 🏦 Estate Data Analysis: *Data-Driven Insights into Real Estate Trends*

📊 **Dashboard**: [View on Tableau Public](https://public.tableau.com/views/estate-market-analysis-dashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📌 Overview

This project is a personal exploration of real estate and customer data. Using Python for preprocessing and analysis, and Tableau for visualization, it aims to identify trends in sales, customer demographics, and building types. While the approach is structured and the results are data-driven, this is a pet project and not intended for professional or commercial use.

## 🎯 Objectives

This analysis seeks to understand the customer profile and building characteristics by answering the following questions:

- Which customer age bracket has the greatest buying potential?
- What is the most sought-after building type?
- Which building type has the highest price?

## 📈 Dashboard

![Dashboard Preview](images/dashboard.png)

## 🧠 Insights

- Most customers were aged **48–71**, primarily middle-aged and senior adults, with the majority residing in **California, USA**.
- **Building 2** is the most in-demand, followed closely by building 3. **Building 5** is the least sought after.
- **Building 2** is also the most expensive. **Building 4** offers the best deal satisfaction; it has the largest area and a moderate mean price.
- A **sales boom occurred in 2007**, followed by a sharp decline in 2008.
- In the U.S., sales were heavily concentrated in a few **top-performing states**.
- The **negative covariance** between `age` and property `price` suggests that the two variables tend to move in opposite directions.
- The **correlation value of -0.17** betwee `age` and property `price` indicates that the linear relationship is very weak, almost nonexistent.

## 🧹 Preprocessing
Key preprocessing steps include:
- Calculating `Customer Age` at time of sale
- Mapping building codes (1–5) to labels or using `pd.dummies`
- Dealing with unnecessary spaces and incorrect data types
- Creating new variables such as `age`
- Merging the two datasets using `customerid`

📝 [View preprocessing notebook](notebooks/1_data_preprocessing.ipynb)

## 📊 Analysis 
- Studied descriptive statistics focusing on buiding, country, and state
- Analyzed customer age in interval categories and properties
- Examined the relationship between customer age and properties (covariance and correlation)

📓 [View analysis notebook](notebooks/2_data_analysis.ipynb)

## 🛠️ Tools & Technologies
- 🐍 Python (data preprocessing & analysis)
- 📊 Tableau (interactive dashboards & visualizations)
- 🐼 pandas 
- 📎 Jupyter Notebook 

## 📂 Dataset

The dataset used in this project was provided as part of the 365 Data Science learning platform. It may not be publicly distributed, so the raw data is not included here.


