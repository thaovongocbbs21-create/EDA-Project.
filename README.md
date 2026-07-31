# Average Monthly Income and Cost of Living Analysis

## Business Analytics Portfolio – Exploratory Data Analysis (EDA)

---

# Project Overview

This project presents an Exploratory Data Analysis (EDA) of a dataset containing information about **Average Monthly Income**, **Cost of Living**, and **Region**.

The objective is to understand the distribution of income, compare average income across different regions, and examine the relationship between monthly income and cost of living through statistical summaries and visualizations.

---

# Dataset Information

**Dataset:** Average Monthly Income and Cost of Living

### Dataset Summary

- Number of observations: **196**
- Number of variables: **5**
- Missing values found: **5**
- Duplicate records: **0**

### Variables

- Year
- Average Monthly Income (USD)
- Cost of Living (USD)
- Region

---

# Data Cleaning

Several preprocessing steps were completed before analysis.

- Checked dataset size and data types
- Identified missing values
- Filled 5 missing values
- Checked duplicate records
- Verified numerical variables
- Prepared the dataset for visualization

The dataset was successfully cleaned and no duplicate records were found after preprocessing.

---

# Descriptive Statistics

Descriptive statistics were generated for the numerical variables.

Main numerical variables include:

- Average Monthly Income (USD)
- Cost of Living (USD)

The descriptive analysis provides information about:

- Mean
- Median
- Minimum
- Maximum
- Standard Deviation

These statistics help summarize the overall characteristics of the dataset before visualization.

---

# Data Visualizations

## 1. Relationship between Average Monthly Income and Cost of Living

![Scatter Plot](images/scatter_plot.png)

### Interpretation

The scatter plot illustrates the relationship between Average Monthly Income and Cost of Living.

The data points are widely scattered across the chart, indicating that there is **no strong linear relationship** between income and cost of living in this dataset.

People with both low and high income levels can experience a wide range of living costs.

---

## 2. Distribution of Average Monthly Income

![Histogram](images/histogram_income.png)

### Interpretation

The histogram shows the distribution of Average Monthly Income.

Income values are relatively spread across different income ranges without significant skewness.

Most observations are evenly distributed throughout the income intervals, suggesting a relatively balanced dataset.

---

## 3. Average Monthly Income by Region

![Bar Chart](images/bar_region.png)

### Interpretation

The bar chart compares the average monthly income across different regions.

Among the six regions:

- Africa has the highest average monthly income.
- Oceania and Europe also have relatively high income levels.
- North America has the lowest average monthly income in this dataset.
- Asia and South America are close to the overall average.

This visualization highlights regional differences in average income.

---

# Key Insights

From the exploratory analysis, several important findings were identified.

### Insight 1

There is **no clear correlation** between Average Monthly Income and Cost of Living based on the scatter plot.

Higher income does not necessarily correspond to higher living costs.

---

### Insight 2

Average Monthly Income varies across regions.

Africa records the highest average income, while North America has the lowest average income among the six regions included in the dataset.

---

# Tools Used

- Microsoft Excel
- Descriptive Statistics
- Histogram
- Scatter Plot
- Bar Chart
- GitHub

---

# Repository Structure

```
EDA-Project
│
├── README.md
├── Average_Monthly_Income.xlsx
└── images
    ├── scatter_plot.png
    ├── histogram_income.png
    └── bar_region.png
```

---

# Author

**Võ Ngọc Phương Thảo**

Business Analytics Student

Eastern International University (EIU)

MIS311 – Business Analytics

---

# Conclusion

This exploratory data analysis provides an overview of income distribution, regional income differences, and the relationship between income and living costs.

The analysis demonstrates how descriptive statistics and visualizations can be used to better understand business data and support data-driven decision making.
