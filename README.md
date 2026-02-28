# 🎮 Gaming Behavior & Health Impact: A Data Analysis Case Study

**Status:** ✅ Completed  
**Focus:** Data Analysis (DA), Statistical Aggregation, Data Visualization  
**Tech Stack:** Python, Pandas, Matplotlib, Seaborn  

---

## 📌 Executive Summary
This project investigates the physiological trade-offs of digital entertainment, specifically focusing on how daily gaming hours impact sleep duration and a user's overall health. By processing raw dataset metrics, engineered features, and statistical visualizations, this study successfully quantifies the "Health Tax" associated with high-intensity gaming and identifies the optimal balance for maintaining well-being.

---

## 🏗️ Project Lifecycle & Methodology

This project was executed through a rigorous, six-phase analytical framework to ensure data integrity and actionable insights.

### 🔹 Phase 1: gaming_data_collection
Raw data is rarely ready for analysis. In this foundational phase, the dataset was sanitized to ensure accuracy:
* **Standardization:** Renamed columns to standardized `snake_case` formats for programmatic consistency.
* **Sanitization:** Handled missing values and verified that numerical columns (like hours and age) were formatted with the correct data types.

### 🔹 Phase 2: gaming_data_cleaning_&_data_preparation
To extract deeper meaning from the raw numbers, we engineered custom metrics that define user behavior:
* **Health Index Creation:** Developed a composite score (`health_index`) to quantify overall well-being based on the balance of sleep and gaming.
* **Behavioral Segmentation:** Created a `gamer_type` feature to categorize users into distinct cohorts: **Casual** (0-2 hours), **Moderate** (3-5 hours), and **Hardcore** (6+ hours).

### 🔹 Phase 3: gaming_EDA_jrm
Visual exploration was conducted to map out the underlying trends in the population:
* **Trend Mapping:** Visualized the distribution of ages and gaming habits.
* **Correlation Discovery:** Identified a strong inverse relationship—proving statistically that as gaming hours increase, sleep hours predictably decrease.

### 🔹 Phase 4: gaming_data_preprocessing_&_outlinear_treatment
Before drawing final conclusions, the data structure was hardened:
* **Outlier Management:** Audited the dataset for extreme anomalies to ensure our final averages were not skewed by isolated cases.
* **Categorical Encoding:** Translated text-based demographic data into numerical formats, structuring the dataset for potential future algorithmic scaling.

### 🔹 Phase 5: gaming_final_result_and_report_jrm
The final phase synthesized the data into clear, actionable business intelligence:
* **Statistical Aggregation:** Grouped the data by `gamer_type` to extract the mean `health_index`, sleep hours, and gaming hours for each cohort.
* **Visual Storytelling:** Generated a comparative "Trade-off" bar chart to visually prove the disparity in habits between Casual and Hardcore gamers.

---

## 💡 Key Insights & Final Verdict

1. **The Sleep Deficit:** The data definitively shows that **Hardcore gamers** sacrifice a significant amount of sleep compared to their Casual counterparts, directly driving down their Health Index.
2. **The Tipping Point:** Health metrics remain relatively stable up to a certain threshold but begin to degrade sharply once gaming exceeds the **5-hour daily mark**.
3. **The Optimal Balance:** To maintain a high Health Index, the data suggests a behavioral "Sweet Spot" of 1–3 hours of daily gaming paired with standard sleep hygiene (7–8 hours).

---
> *Analysis conducted and documented by Jayanth Rao.*
