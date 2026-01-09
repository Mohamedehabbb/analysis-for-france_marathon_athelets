# 🏃 Ultra-Marathon Athletes Analysis (France)
### Data Analysis Project

---

## 👋 Project Overview
This project analyzes a subset of **The Big Dataset of Ultra-Marathon Running**, focusing on **athletes participating in ultra-marathon events in France**.

The goal is to explore athlete demographics, race characteristics, and performance patterns using a structured **Data Analysis workflow**.

---

## ❓ Problem Statement
Ultra-marathon races generate massive amounts of data, but raw data alone does not provide insights.

**Key questions addressed in this project:**
- What are the main characteristics of ultra-marathon athletes in France?
- How do age, gender, and race distance relate to performance?
- What trends can be observed in ultra-marathon participation and results?

---

## 🎯 Project Objectives
- Clean and prepare a large real-world dataset
- Analyze athlete demographics and race information
- Explore performance trends and distributions
- Practice working with large, noisy datasets
- Communicate insights through visual analysis

---

## 🧠 Dataset Description
**Dataset Name:** The Big Dataset of Ultra-Marathon Running  
**Subset:** France Ultra-Marathon Events

### Dataset Characteristics
- Very large-scale real-world dataset
- Combination of numerical and categorical features
- Contains athlete, race, and performance information
- Noisy and heterogeneous (real competition data)

### Typical Features
- Athlete information (age, gender, nationality)
- Race details (distance, event name, location)
- Performance metrics (finish time, ranking)

> ⚠️ Due to the large size of the dataset, raw data is not included in this repository.

---

## 🔄 Step-by-Step Data Analysis Workflow

### 1️⃣ Data Loading
- Imported the dataset using Pandas
- Inspected dataset size and structure
- Reviewed column names and data types

---

### 2️⃣ Data Understanding & Inspection
- Displayed sample rows
- Checked data types and basic statistics
- Identified important columns for analysis

**Why this step matters:**  
Understanding the structure of the data is essential before any cleaning or analysis.

---

### 3️⃣ Data Cleaning
- Handled missing and invalid values
- Converted data types where necessary
- Filtered the dataset to focus on **France-based events**
- Removed irrelevant or duplicated records

**Challenge:**  
Real-world sports data contains inconsistencies and incomplete records.

---

### 4️⃣ Exploratory Data Analysis (EDA)
- Analyzed athlete age distribution
- Studied gender participation
- Explored race distances and frequency
- Examined performance metrics (time, ranking)

**Key Observations:**
- Participation varies significantly across age groups
- Male athletes dominate ultra-marathon participation
- Longer distances show fewer finishers and higher variability

---

### 5️⃣ Visualization
Used visualizations to better understand patterns:
- Distribution plots
- Bar charts for categorical analysis
- Histograms for age and performance metrics

**Purpose:**
- Identify trends
- Detect outliers
- Communicate insights clearly

---

### 6️⃣ Insights & Findings
- Ultra-marathon participation is skewed toward specific age ranges
- Performance varies strongly with distance
- Data reflects realistic endurance-sport behavior and constraints

---

## 📊 Project Structure
```text
ultra-marathon-analysis/
│── analysis-for-france-marathon-athelets.ipynb
│── README.md
│── requirements.txt
