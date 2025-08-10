# 🌲 Forest Fire Data Analysis

### 📌 Overview
This project analyzes the Forest Fires dataset to uncover patterns, trends, and correlations between environmental factors and fire severity.
Using Python’s data analysis libraries, the notebook performs data preprocessing, exploratory data analysis (EDA), and visualizations to derive actionable insights.

### 📂 Dataset
The dataset contains:

Time Variables: month, day

Weather Conditions: temp, RH (relative humidity), wind, rain

Fire Weather Indices: FFMC, DMC, DC, ISI

Target: area — hectares burned

### 🎯 Objectives
Preprocess and clean the dataset for analysis.

Explore seasonal trends in forest fires.

Examine relationships between weather conditions and burned area.

Identify the most influential factors on fire severity.

Present findings through statistical summaries and visualizations.

### 🛠 Tools & Libraries
Python 3

Jupyter Notebook

Pandas — Data manipulation

NumPy — Numerical operations

Matplotlib — Static visualizations

Seaborn — Statistical visualizations

### 📊 Analysis Steps
Data Loading — Import dataset using Pandas.

Data Cleaning:

Convert categorical month/day names to numerical form.

Handle missing or outlier values.

Exploratory Data Analysis:

Distribution plots for each variable.

Correlation analysis with heatmaps.

Monthly and daily trend visualizations.

Insights Extraction:

Key patterns in fire occurrences.

Environmental factors influencing fire spread.

Conclusion & Recommendations.

### 🔍 Key Insights
August and September have the highest fire activity.

Fires are more severe in high temperature, low humidity, and windy conditions.

DC (Drought Code) and ISI (Initial Spread Index) show strong correlation with burned area.

### 🚀 How to Run the Project
1. Clone the repository:
    git clone https://github.com/yourusername/forest-fire-analysis.git
    cd forest-fire-analysis
2. Install dependencies:
    pip install pandas numpy matplotlib seaborn
3. Launch Jupyter Notebook:
    jupyter notebook forest_fire.ipynb
4. Run all cells to reproduce the analysis.

