# 🍽️ Zomato Restaurant Analytics Dashboard (Power BI)

## 📌 Project Overview

This project focuses on analyzing Zomato restaurant data to extract meaningful business insights using **Power BI**. The goal is to understand restaurant distribution, customer preferences, pricing trends, and locality-based performance.

The dashboard provides an **interactive and visual representation** of the dataset, enabling users to explore patterns and make data-driven decisions.

---

## 🎯 Objectives

* Analyze restaurant distribution across locations
* Identify popular cuisines and their demand
* Understand customer engagement through votes
* Evaluate pricing trends and affordability
* Discover locality-wise performance gaps
* Provide a decision-support tool using interactive visuals

---

## 📊 Key Features of Dashboard

### 🔢 KPI Cards

* Total Restaurants
* Average Rating
* Average Cost for Two
* Total Votes
* Number of Cuisines
* Number of Localities

👉 These KPIs give a quick overview of the dataset.

---

### 🌍 Geographic & Distribution Analysis

* Restaurant distribution across locations
* Helps identify high-density and low-density areas

---

### 🌳 Cuisine Distribution (Treemap)

* Shows most popular cuisines
* Helps understand customer preferences

---

### 🔥 Locality vs Cuisine Heatmap

* Displays average ratings across locations and cuisines
* Identifies:

  * High-performing areas
  * Under-served markets

---

### 📊 Top Restaurants Table

* Top 10 restaurants based on votes
* Includes:

  * Rating
  * Cost
  * Location
  * Popularity

---

### 🎚️ Interactive Filters (Slicers)

* City selection (Dropdown)
* Rating range (Slider)
* Price range (Slider)

👉 Allows dynamic exploration of data

---

## 🧹 Data Preprocessing

Data cleaning and transformation were performed using Python (Jupyter Notebook):

* Handled missing values
* Cleaned and formatted columns
* Split multi-value columns (like cuisines)
* Converted data types for analysis
* Prepared dataset for Power BI

---

## 🛠️ Tools & Technologies Used

* **Python (Pandas, NumPy)** → Data Cleaning
* **Jupyter Notebook (.ipynb)** → Preprocessing
* **Power BI** → Data Visualization & Dashboard
* **DAX** → Calculated measures

---

## 🧠 Key Insights

* Certain cuisines dominate specific localities
* High ratings are not always correlated with high cost
* Some areas have high demand but fewer restaurant options
* Popular restaurants are driven by both rating and votes

---

## 🚀 How to Use the Dashboard

1. Open the `.pbix` file in Power BI Desktop
2. Use filters on the left panel:

   * Select City
   * Adjust Rating range
   * Adjust Price range
3. Interact with visuals:

   * Click on cuisines or locations to filter data
4. Analyze patterns across:

   * Ratings
   * Cost
   * Popularity

---

## 📁 Project Structure

```
├── zomato_cleaned.csv        # Cleaned dataset
├── data_preprocessing.ipynb  # Data cleaning notebook
├── Zomato Dashboard.pbix     # Power BI dashboard
└── README.md                 # Project documentation
```

---

## 💡 What This Project Demonstrates

* Data cleaning and preprocessing skills
* Strong understanding of business problems
* Data visualization and storytelling
* Use of Power BI for real-world analytics
* Ability to build interactive dashboards

---

## 📈 Future Improvements

* Add time-based analysis (if data available)
* Include sentiment analysis from reviews
* Deploy dashboard online (Power BI Service)
* Enhance UI/UX with advanced design elements

---

## 🙋‍♀️ Author

**Pragya Pandey**

---

⭐ If you found this project useful, feel free to give it a star!
