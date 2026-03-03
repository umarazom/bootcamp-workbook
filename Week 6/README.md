# 📊 Week 6 – Global Economic Data Analysis (Python)

## 🔎 Project Overview

This project explores global GDP per capita data using estimates from the IMF, United Nations, and World Bank.

The objective was to:

- Clean and prepare real-world economic data
- Perform exploratory data analysis (EDA)
- Compare international reporting sources
- Identify global economic patterns
- Extract business-level insights from statistical outputs

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📌 Project Structure

### 1️⃣ Data Preparation
- Imported CSV dataset
- Checked data types and structure
- Identified missing and zero values
- Cleaned inconsistencies
- Standardised numeric columns

### 2️⃣ Exploratory Data Analysis (EDA)
- Descriptive statistics (`describe()`)
- Distribution analysis (histograms)
- Region-based grouping (`groupby`)
- Correlation analysis
- Visualisation for insight communication

---

# 📊 Key Analysis & Visualisations

---

## 📈 GDP Distribution Analysis

Understanding the spread and skewness of GDP per capita values.

![GDP Distribution Histogram](images/week6-gdp-distribution-histogram.png)

### Insight
- GDP per capita is strongly right-skewed.
- A small number of high-income countries significantly increase the global average.
- Most countries cluster in lower-to-mid income ranges.

This highlights global economic imbalance.

---

## 🌍 Average GDP per Capita by UN Region

Regional aggregation using `groupby()` and mean calculations.

![Average GDP by Region](images/week6-gdp-average-by-region.png)

### Insight
- Europe shows the highest regional average GDP.
- Africa shows the lowest average GDP.
- Clear structural economic disparity exists between regions.

This type of analysis is commonly used in economic benchmarking and policy comparison.

---

## 🔎 Countries Below the Global Average (IMF)

Calculated the global IMF average and filtered countries below this benchmark.

![Countries Below World Average](images/week6-below-world-average.png)

### Insight
- Identifies developing and emerging economies.
- Demonstrates ability to create comparative baselines.
- Shows analytical filtering beyond simple descriptive statistics.

This reflects real-world business analysis thinking.

---

## 📊 Correlation Between IMF, UN & World Bank Estimates

Correlation matrix to evaluate consistency across reporting bodies.

![Correlation Heatmap](images/week6-correlation-heatmap.png)

### Insight
- IMF and World Bank estimates show extremely strong correlation (~0.99).
- UN estimates are also highly aligned.
- Confirms reliability and consistency across major economic institutions.

Demonstrates understanding of statistical relationships.

---

# 🧠 Analytical Skills Demonstrated

- Data cleaning and preprocessing
- Handling missing and zero values
- Distribution analysis
- Statistical aggregation
- Correlation analysis
- Business interpretation of numeric outputs
- Visual storytelling with data
- Structured exploratory workflow

---

# 💼 Recruiter Relevance

This project demonstrates:

✔ Independent analysis of real-world global datasets  
✔ Strong command of Pandas operations (`groupby`, filtering, aggregation)  
✔ Ability to translate statistics into business insight  
✔ Professional-quality visualisations  
✔ Structured and logical analytical workflow  

This reflects practical junior data analyst capability rather than academic-only exercises.

---

# 🚀 Next Improvements (Future Iteration)

- Add regression analysis
- Build interactive dashboard (Streamlit / Power BI)
- Compare GDP trends over time
- Integrate additional macroeconomic indicators

---
