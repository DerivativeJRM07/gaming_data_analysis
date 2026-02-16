# 🎮 Impact of Gaming on Health: A Predictive Analysis
**Author:** [Your Name]  
**Project Status:** 🟡 Phase 4 Complete | Phase 5 (Machine Learning) Upcoming  
**Date:** February 16, 2026

## 📌 Project Overview
This research-driven project investigates the correlation between daily gaming intensity, sleep hygiene, and physiological/psychological health outcomes. By leveraging data science workflows, we aim to move beyond simple observations to build a machine-learning model capable of predicting a user's **Health Index** based on their behavioral patterns.

---

## 📁 Data Architecture & Lifecycle
To maintain high scientific standards, the data is organized into three distinct stages within the `/data` directory:

1. **`Gaming_Hours_vs_Performance_1000_Rows.csv`**: The "original file". The "Raw" source. No modifications. This preserves the integrity of the starting point. 
2. **`gaming_data_ready_for_eda.csv`**: The after data cleaningp file. the "Transformed" source. Includes renamed columns and engineered features (like Health Index). Used for all human-readable visualizations.
3. **`gaming_data_ready_to_ML_data_preprocessing.csv`**: The "Final" source. Outliers have been handled via the IQR method, and categorical variables have been converted to Numerical IDs (Encoding) for algorithm compatibility.

---

## 🛠️ Executed Research Phases

### 🔹 Phase 1: Data Sanitization & Structural Alignment
* **Integrity Check:** Scanned for null values and data inconsistencies.
* **Normalization:** Standardized column naming conventions (e.g., `daily_gaming_hours`) for cleaner coding.

### 🔹 Phase 2: Feature Engineering & Domain Logic
* **Metric Creation:** Developed a **Health Index** score—a weighted calculation that balances gaming time against restorative sleep.
* **Segmentation:** Implemented logic to classify users into **Casual, Moderate, and Hardcore** tiers based on their daily engagement.

### 🔹 Phase 3: Exploratory Data Analysis (EDA)
We utilized **Seaborn** and **Matplotlib** to uncover hidden trends:
* **Univariate Insights:** Examined the density and distribution of gaming habits across the population.
* **Bivariate Correlation:** Confirmed a visible decline in sleep duration as gaming hours surpassed the 4-hour threshold.
* **Multivariate Complexity:** Used `sns.pairplot` and `FacetGrids` to analyze how **Gender** acts as a mediating variable in these behaviors.

### 🔹 Phase 4: Preprocessing & Statistical Cleaning
* **Outlier Analysis:** Conducted a Boxplot audit using the **Interquartile Range (IQR)** method. 
* **Statistical Result:** 0 extreme outliers detected, indicating a high-quality, realistic dataset.
* **Categorical Encoding:** Leveraged `LabelEncoder` to transform text-based categories (Gender, Gamer Type) into numerical formats, enabling mathematical modeling.

---

## 📊 Technical Stack
* **Language:** Python 3.x
* **Libraries:** Pandas (Data Manipulation), NumPy (Math), Seaborn/Matplotlib (Visualization), Scikit-Learn (Preprocessing).
* **Environment:** Google Colab / Jupyter Notebooks.

---

## 🔮 Roadmap: Phase 5 (Predictive Modeling)
Our next objective is to transition from **Historical Analysis** to **Predictive Intelligence**.

1. **Data Splitting:** Implementing an 80/20 Train-Test split to ensure the model generalizes well to new data.
2. **Algorithm Selection:** Training a **Linear Regression** or **Random Forest** model to predict the Health Index.
3. **Performance Metrics:** Evaluating the model using **Mean Squared Error (MSE)** and **R-Squared** scores.
4. **Insight Extraction:** Determining which feature (Age, Sleep, or Gaming) is the strongest predictor of overall health.

---
*This project is updated iteratively. Last documentation update: February 2026.*
