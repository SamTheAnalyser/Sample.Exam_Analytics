# Sample.Exam_Analytics
Python project that automatically generates detailed dataset reports with visualizations, including histograms, boxplots, value counts, and correlation heatmaps. Ideal for exploratory data analysis and quick insights for datasets.
# Dataset Report Generator

## Overview
This Python project automatically generates detailed HTML reports for any dataset. The reports include:

- Dataset overview: number of rows and columns
- Missing values summary
- Column types and basic statistics
- Visualizations for numeric columns (histograms and boxplots)
- Visualizations for categorical columns (top categories bar plots)
- Correlation heatmap for numeric features
- Automated insights like highest correlation and columns with most missing values

This tool is perfect for exploratory data analysis (EDA) and quick dataset insights.

---

## Features

1. **Numeric Columns Visualization**
   - Histograms with KDE
   - Boxplots for outlier detection

2. **Categorical Columns Visualization**
   - Top 10 categories bar plots

3. **Correlation Analysis**
   - Heatmap for numeric features

4. **Automated Insights**
   - Column with most missing values
   - Pair of numeric columns with highest correlation

---

## Requirements

- Python 3.7+
- Pandas
- Matplotlib
- Seaborn

You can install the required packages with:

```bash
pip install pandas matplotlib seaborn
