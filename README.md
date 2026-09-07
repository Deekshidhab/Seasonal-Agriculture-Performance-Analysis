# Seasonal Agriculture Performance Analysis

## 📌 Project Overview
This project evaluates agricultural activities across different seasons (**Kharif**, **Rabi**, and **Zaid**) using data analytics[cite: 1]. The primary goal is to investigate how environmental conditions, farming practices, and resource usage impact crop yield and overall economic performance[cite: 1].

---

## 🎯 Problem Statement
Agricultural outcomes vary significantly across seasons due to changing environmental conditions, resource availability, and input costs[cite: 1]. Raw agricultural data does not readily explain these performance variations[cite: 1]. This project analyzes seasonal patterns, trends, and efficiency metrics to support evidence-based agricultural planning[cite: 1].

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python 3.x
* **Libraries Used:**
  * **Data Analysis:** `pandas`, `numpy`
  * **Data Visualization:** `matplotlib`, `seaborn`
  * **Statistical Testing:** `scipy.stats` (One-Way ANOVA)
* **Development Environment:** Jupyter Notebook

---

## 📊 Key Findings & Insights
* **Kharif Season (Peak Profitability):**
  * **Average Yield:** 5.64 Tonnes/Ha
  * **Average Profit:** ₹178,914.65
  * High rainfall (852.08 mm) and higher soil moisture (31.20%) create optimal crop growing conditions.
* **Rabi Season (Moderate Output):**
  * **Average Yield:** 5.08 Tonnes/Ha
  * **Average Profit:** ₹87,689.47
  * Characterized by cooler temperatures (23.49°C) and moderate rainfall (436.00 mm).
* **Zaid Season (High Risk & Financial Loss):**
  * **Average Yield:** 4.67 Tonnes/Ha
  * **Average Profit:** -₹24,804.82 (Average Loss)
  * Extreme heat (31.04°C) and higher water requirements (6,419.89 m³) result in low water efficiency (4.41 tonnes/1000m³) and financial losses.

---

## 💡 Recommendations
1. **Zaid Crop Substitution:** Avoid cultivating water-intensive crops during the Zaid season to minimize financial loss.
2. **Resource Optimization:** Implement drip and micro-irrigation systems during dry seasons to improve water efficiency and reduce operating costs.
3. **Kharif Investment:** Maximize capital allocation during Kharif to capitalize on favorable environmental conditions.

---

## 📁 Repository Structure
```text
.
├── README.md                                # Project documentation
├── VOIS_Major_Project_PPT_VOIS...           # Major project presentation slides
├── seasonal_agriculture_performance.ipynb   # Analysis notebook with code & visualizations
└── seasonal_agriculture_performance_dataset.csv # Dataset used for agricultural analysis
