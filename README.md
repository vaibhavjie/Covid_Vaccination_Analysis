# 🦠 COVID-19 Vaccination Data Analysis & Visualization

This project explores global COVID-19 vaccination data using data cleaning, exploratory data analysis (EDA), and advanced visualizations including line charts, pie charts, doughnut charts, bar plots, and heatmaps.

---

## 📂 Dataset Details

- **Source**: [Kaggle - COVID-19 World Vaccination Progress](https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress)
- **File Used**: `country_vaccinations.csv`
- **Columns**:
  - `country`
  - `date`
  - `total_vaccinations`
  - `people_vaccinated`
  - `people_fully_vaccinated`
  - `daily_vaccinations`
  - `vaccines`
  - `source_name`
  - `source_website`

---

## 🧹 Data Cleaning Steps

- Converted `date` column to datetime format.
- Filled missing values in:
  - `daily_vaccinations`, `people_vaccinated`, `people_fully_vaccinated` with 0
- Converted necessary columns to numeric type using `pd.to_numeric()`.
- Removed percentage signs, symbols, and inconsistencies in string values.

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Visualizations Performed:

1. **Line Chart**:  
   Vaccination trends over time for India  
   ➤ `plt.plot()` shows how people were vaccinated daily and fully over time.

2. **Pie Chart**:  
   Top 5 countries with the highest total vaccinations  
   ➤ `plt.pie()` shows percentage distribution.

3. **Doughnut Chart**:  
   Top 5 vaccine combinations used globally  
   ➤ Pie chart with a center circle using `plt.Circle()`.

4. **Bar Plot**:  
   Daily vaccinations in India for the last 30 days  
   ➤ `sns.barplot()` compares each day's vaccination count.

5. **Heatmap**:  
   Correlation between numeric vaccine metrics  
   ➤ `sns.heatmap()` shows relationships (e.g., people vaccinated vs. fully vaccinated).

---

---

## 🧠 Tools & Libraries Used

 Tool           Purpose                            
 pandas       Data loading and manipulation       
matplotlib   Plotting (line, pie, doughnut)      
 seaborn     Statistical plots (bar, heatmap)    
 numpy        Numerical support (for circle)      

---

## 📌 Key Learnings

- How to clean real-world time-series and percentage-based data
- Line and bar plots for time-based analysis
- Pie and doughnut charts for proportional visualization
- Correlation analysis using heatmaps





