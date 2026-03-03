# 911-calls-capstone-project
📌 Project Overview

This project explores a real-world dataset of 911 emergency calls to uncover patterns, trends, and insights using Python data analysis and visualization techniques.

The goal is to answer questions like:

What are the most common reasons people call 911?

How do call volumes change over time?

Are there peak hours, days, or months?

Do different emergencies show seasonal patterns?

This project focuses on data cleaning, exploratory data analysis (EDA), feature engineering, and visualization.

🗂 Dataset Information

Dataset: Montgomery County, PA 911 Calls

Features include:

lat – Latitude

lng – Longitude

desc – Call description

zip – Zip code

title – Emergency category

timeStamp – Date & time of call

twp – Township

addr – Address

Tech Stack

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Google Colab

🔍 Key Steps Performed

1️⃣ Data Cleaning

Checked for missing values

Converted timeStamp to datetime format

Extracted:

Hour

Month

Day of Week

2️⃣ Feature Engineering

Extracted main emergency category from title column

EMS

Fire

Traffic

3️⃣ Exploratory Data Analysis

Most common emergency types

Top zip codes for 911 calls

Calls by:

Hour

Day of week

Month

4️⃣ Visualizations

Count plots

Line plots for trends

Heatmaps

Correlation analysis

📊 Key Insights

🚑 EMS calls are the most frequent category.

📅 Certain weekdays show higher call volumes.

🕒 Peak emergency hours occur during daytime.

📈 Clear time-based trends exist across months.
e – Dummy variable (always 1)
