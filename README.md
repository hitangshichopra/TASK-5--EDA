# 🎢 Roller Coaster Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This notebook presents an exploratory data analysis (EDA) of a **Roller Coaster dataset**, using **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to clean the data, understand its structure, visualize patterns, and answer analytical questions about the characteristics and trends of roller coasters worldwide.

---

## 🎯 Objectives

- Understand the dataset structure and contents
- Clean and prepare the data for analysis
- Perform univariate and multivariate analysis
- Explore correlations and trends
- Answer analytical questions with visual support

---

## 🛠️ Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 📁 Dataset

- **Dataset Name:** Roller Coaster Dataset  
- **Features Include:** Coaster name, park name, location, status, speed, height, material type, design type, year introduced, etc.

---

## 🔍 EDA Workflow

### ✅ Step 0: Setup & Data Loading
- Imported necessary Python libraries
- Loaded the dataset using `pandas.read_csv()`

### ✅ Step 1: Data Understanding
- Explored the data using:
  - `shape`, `head()`, `tail()`
  - `dtypes`, `describe()`
- Understood the general structure and summary statistics of the dataset

### ✅ Step 2: Data Preparation
- Dropped irrelevant or duplicate columns
- Renamed columns for clarity
- Created additional features to support analysis
- Ensured data consistency and handled missing values

### ✅ Step 3: Feature Understanding (Univariate Analysis)
- Explored individual variables using:
  - Histograms
  - KDE plots
  - Boxplots
- Focused on key metrics like coaster height, speed, and year of introduction

### ✅ Step 4: Feature Relationships (Bivariate/Multivariate Analysis)
- Used visual tools to understand feature interactions:
  - Scatterplots
  - Heatmaps (correlation matrix)
  - Pairplots
  - Groupby summaries to compare coaster types, materials, and operational status

### ✅ Step 5: Analytical Question
**"What are the locations with the fastest roller coasters (minimum of 10)?"**
- Grouped data by location and calculated average speed
- Visualized results to identify hotspots for high-speed coasters

---

## 📊 Key Insights

- Steel coasters generally have greater height and speed compared to wooden coasters
- Certain regions (e.g., the USA, Japan) feature faster roller coasters on average
- Modern coasters introduced in recent decades tend to be faster and taller
- Specific coaster types and materials are associated with higher performance

---

## 🧠 Skills Demonstrated

- Data cleaning and preparation
- Univariate and multivariate analysis
- Correlation and relationship analysis
- Visualization with Matplotlib & Seaborn
- Drawing data-driven conclusions




