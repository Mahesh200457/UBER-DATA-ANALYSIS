
# 🚕 Uber Rides Data Analysis

This project focuses on analyzing Uber ride data to help the company understand customer behavior and preferences. The goal is to answer key business questions such as ride categories, purposes, time trends, and distance insights to assist Uber in optimizing its services.

---

## 🎯 Business Questions

As a data analyst at Uber, your task is to answer the following:

1. 🏷️ **In which category** do people book the most Uber rides?
2. 🎯 **For which purpose** do people book Uber rides the most?
3. 🕒 **At what time** do people book cabs the most from Uber?
4. 📅 **In which months** do people book Uber rides less frequently?
5. 📆 **On which days** of the week do people book Uber rides the most?
6. 📏 **How many miles** do people usually book a cab for through Uber?

---

## 📂 Dataset

- **Source**: [Kaggle Uber Rides Dataset](https://www.kaggle.com/)
- **Columns include**:
  - `Category` (e.g., Business, Personal)
  - `Purpose` (e.g., Meeting, Commute, Travel)
  - `Start Date`, `End Date`
  - `Miles`, `Duration`, `Start`, `Stop`

---

## 📊 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 🔧 Steps Performed

### 1️⃣ Data Preprocessing
- Handle missing values
- Convert date columns to datetime format
- Extract month, day, and hour from timestamps
- Clean and format `Purpose` and `Category` columns

### 2️⃣ Exploratory Data Analysis (EDA)
- Count most frequent ride categories
- Analyze top ride purposes
- Time-based analysis: hour of day, day of week, month
- Compute average miles per ride
- Visualize trends with barplots and line plots

---

