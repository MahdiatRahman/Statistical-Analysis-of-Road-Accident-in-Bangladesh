# 🚗 Statistical Analysis of Road Accident Patterns and Severity Outcomes in Bangladesh

A research-based statistical analysis of road traffic accident patterns in Bangladesh using a real-world dataset of approximately **49,000 accident records**. This project explores the factors influencing accident severity through descriptive statistics, hypothesis testing, regression analysis, and data visualization to support evidence-based road safety recommendations.

> 📌 **Status:** Research Poster Accepted at Multiple Academic Conferences

---

## 📖 Abstract

Road safety has become a critical issue due to increasing injuries, fatalities, and economic losses, particularly in Bangladesh where rapid urbanization and high vehicle density contribute to accident risks. This study performs statistical analysis on a large real-world road accident dataset containing both qualitative and quantitative variables.

The dataset was cleaned, preprocessed, analyzed, and visualized to identify accident patterns and the major factors associated with accident severity. The findings provide data-driven insights that can support policymakers, transportation authorities, and researchers in improving road safety strategies.

---

# 🎯 Research Objectives

- Analyze road accident patterns in Bangladesh.
- Identify the major factors influencing accident severity.
- Perform statistical hypothesis testing.
- Visualize accident trends using descriptive statistics.
- Support data-driven road safety and transportation policies.

---

# 📂 Dataset

- **Dataset Type:** Real-world Road Traffic Accident Dataset
- **Records:** ~49,000
- **Variables:** 30+

### Major Variables

- Accident Intensity
- Driver Age
- Vehicle Count
- Injury Count
- Death Count
- Road Type
- Traffic Control
- Weather Condition
- Lighting Condition
- Road Surface
- Junction Type
- Traffic Condition

---

# 🛠 Data Preprocessing

The dataset was cleaned before analysis using Microsoft Excel and Python.

### Cleaning Steps

- Removed duplicate records
- Checked missing values
- Removed unrealistic values
- Detected outliers using the **Interquartile Range (IQR)** method
- Standardized categorical values
- Organized variables for statistical analysis

---

# 📊 Exploratory Data Analysis

The project includes several visualizations to understand accident characteristics.

### Qualitative Analysis

- Bar Charts
- Pie Charts

Used to analyze:

- Traffic Control
- Accident Intensity
- Road Types
- Weather Conditions

### Quantitative Analysis

- Histogram
- Scatter Plot
- Frequency Curve

Used to analyze:

- Driver Age Distribution
- Injury Count Distribution
- Vehicle Count
- Death Count

---

# 📈 Statistical Analysis

## Correlation Analysis

**Hypothesis**

> Injury count is related to accident severity.

### Result

No statistically significant relationship was found between injury count and accident severity.

### Interpretation

Accident severity is influenced by multiple factors rather than only the number of injuries.

---

## Independent T-Test

**Hypothesis**

> Accident severity differs between daylight and nighttime.

### Result

The analysis was inconclusive due to insufficient or imbalanced lighting-condition data.

### Interpretation

No reliable conclusion could be drawn regarding the effect of lighting conditions on accident severity.

---

## Chi-Square Test

**Hypothesis**

> Weather conditions affect accident risk.

### Result

Weather conditions and accident risk were found to be statistically independent.

### Interpretation

Weather alone is not a strong predictor of accident risk within this dataset.

---

## Multiple Linear Regression

### Purpose

To identify the variables that significantly influence accident risk.

### Significant Variables

- Vehicle Count
- Fatalities (Death Count)

### Non-significant Variable

- Injury Count

### Interpretation

Accident risk is more strongly associated with traffic complexity and fatal outcomes than with injury count alone.

---

# 📊 Key Findings

- Multi-vehicle accidents contribute to higher accident severity.
- Uncontrolled intersections experience more accidents than controlled intersections.
- Drivers in their mid-twenties appear most frequently in accident records.
- Most accidents result in only 0–1 injuries.
- Vehicle count is a stronger predictor of accident risk than injury count.
- Weather conditions alone do not significantly determine accident risk.
- Accident severity is influenced by multiple interacting factors rather than a single variable.

---

# 💻 Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

### Software

- Microsoft Excel
- Jupyter Notebook
- Visual Studio Code

---

# 📁 Project Structure

```
Road-Accident-Analysis/
│
├── Dataset/
│   ├── Raw Dataset
│   └── Cleaned Dataset
│
├── Notebooks/
│   └── Data Analysis.ipynb
│
├── Images/
│   ├── Bar Charts
│   ├── Histograms
│   ├── Scatter Plots
│   └── Frequency Curves
│
├── Poster/
│   └── Research Poster.pdf
│
├── README.md
└── requirements.txt
```

---

# 📚 Research Conclusion

Road accident severity in Bangladesh is a multifactor problem that cannot be explained by a single variable. The analysis indicates that traffic characteristics, multi-vehicle collisions, uncontrolled intersections, and fatal outcomes have stronger relationships with accident risk than injury count or weather conditions alone.

These findings demonstrate the importance of comprehensive traffic management and evidence-based policymaking to improve road safety.

---

# 📌 Future Work

- Apply machine learning models for accident severity prediction.
- Incorporate GIS-based spatial analysis.
- Develop interactive dashboards for accident monitoring.
- Analyze temporal accident trends using time-series methods.
- Compare accident patterns across different regions of Bangladesh.

---

# 👨‍💻 Author

**Mahdiat Rahman**


# 👨‍💻 Co Author

FARDEEN KABIR

# 👨‍💻 SUPERVISED BY

Dr FATEMA TUZ ZUHRA
