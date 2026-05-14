# 📺 Amazon Prime Video Data Analysis Dashboard

A complete end-to-end Data Analytics project that analyzes the  Prime Video dataset using Python for data cleaning and preprocessing and  Power BI for interactive dashboard creation.

This project provides valuable insights into Amazon Prime Video content, including movies and TV shows, based on genres, ratings, release years, countries, and content types.

---

## 🚀 Project Overview

The objective of this project is to:

- Clean and preprocess raw Amazon Prime Video data using Python.
- Handle missing values and transform columns into a structured format.
- Connect the cleaned dataset to Power BI.
- Create an interactive and visually appealing dashboard.
- Generate business insights from the data.

---

## 📌 Key Insights

The dashboard answers important questions such as:

- 🎬 Total number of Movies and TV Shows available on Amazon Prime Video.
- 🌍 Which countries produce the most content.
- 📈 Content growth over the years.
- ⭐ Distribution of content ratings (PG, R, TV-14, etc.).
- 🎭 Most popular genres.
- 🗓 Trends in release years.
- 📺 Comparison between Movies and TV Shows.

---

## 🛠️ Tech Stack

- 🐍 Python
- 📊 : Power BI
- 🐼 : Pandas
- 🔢 : NumPy
- 📓 : Jupyter Notebook

---

## 📂 Project Structure


Amazon-Prime-Data-Analysis

│── dashboard/
│   └── Amazon.pbix


**Data Cleaning Steps (Python)**

The dataset was cleaned using Python with the following steps:

Imported the dataset using Pandas.
Checked for missing values.
Removed duplicate records.
Converted date columns to proper datetime format.
Split multi-value columns such as Genre and Country.
Standardized text formatting.
Exported the cleaned dataset to CSV.
Connected the cleaned data to Power BI.

**📊 Dashboard Features**

The Power BI dashboard includes:

KPI Cards (Total Titles, Movies, TV Shows)
Genre Distribution Chart
Country-wise Content Map
Release Year Trend Analysis
Ratings Breakdown
Interactive Filters and Slicers
