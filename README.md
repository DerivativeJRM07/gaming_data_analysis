# 🎮 Gaming Habits & Health Analysis
### *Exploratory Data Analysis (EDA) & Impact Study*

## 📌 Project Overview
This project investigates how gaming habits influence physical health and sleep patterns. By applying statistical analysis and data visualization, we aim to uncover the "tipping point" where gaming transitions from a hobby to a potential health risk.

## 🛠️ Data Science Toolkit
* **Language:** Python 3.x
* **Platform:** Google Colab
* **Key Libraries:** `Pandas` (Data Manipulation), `Seaborn` & `Matplotlib` (Advanced Visualization), `NumPy` (Numerical Analysis).

## 🚀 Accomplishments & Workflow

### 1. Data Architecture & Cleaning
* **Refined Schema:** Standardized column names and handled null values for a clean analysis environment.
* **Feature Engineering:** * Developed a custom **`Health_Index`** to quantify wellness based on sleep-to-gaming ratios.
    * Implemented dynamic **`Gamer_Type`** classification (*Casual*, *Regular*, *Hardcore*) using threshold-based logic.

### 2. Univariate Analysis (Distribution Study)
* **Gamer Profiling:** Used `sns.countplot` with modern palettes (`magma`, `crest`) to identify that "Regular" gamers constitute the largest segment.
* **Density Insights:** Generated **Histograms with KDE curves** for `daily_gaming_hours` to visualize data skewness and frequency peaks.
* **Gender Metrics:** Verified population balance to ensure comparative studies are statistically sound.

### 3. Bivariate Analysis (Relationship Mapping)
* **Gaming vs. Sleep:** Created **Regression Plots** (`sns.regplot`) showing the direct impact of gaming hours on rest cycles.
* **Grouped Distributions:** Utilized **Box Plots** to compare sleep variability across different gamer categories.
* **Categorical Heatmaps:** Constructed **Cross-tabulated Heatmaps** to visualize the density of gamer types across genders.

## 📊 Preliminary Insights
* **The Sleep Gap:** Initial findings suggest a notable negative correlation between high daily gaming hours and average sleep duration.
* **Optimization:** All visualization code is optimized for **Seaborn v0.14.0+**, utilizing explicit `hue` mapping to ensure high-performance rendering and no deprecation warnings.

## 📅 Roadmap (Upcoming)
- [ ] **Multivariate Analysis:** Analyzing the 3-way interaction between Gender, Gaming, and Health.
- [ ] **Outlier Removal:** Using Interquartile Range (IQR) to clean extreme data points.
- [ ] **Final Correlation Matrix:** Summarizing all numerical features into a final impact heatmap.

---
*Last Updated: February 2026*
