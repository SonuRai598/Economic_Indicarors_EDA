# 📊 Exploratory Data Analysis of Global Economic Indicators (2010–2023)

## 📝 Project Overview

This project analyzes global economic indicators from 2010 to 2023, including GDP growth, inflation, unemployment, and interest rates across multiple countries. The goal is to explore trends, relationships, and economic performance over time.


## 📂 Dataset

- Source file: `economic_indicators_dataset_2010_2023.csv`
- Time span: 2010–2023
- Key columns: Date, Country, Inflation Rate, GDP Growth Rate, Unemployment Rate, Interest Rate


## 🔧 Data Processing

- Converted dates to datetime format for consistency. 🗓️
- Removed duplicates and handled negative values by clipping them to zero. ❌➡️0
- Standardized column names for easier analysis. 🆔
- Selected relevant columns for focused analysis. 🎯


## 📈 Analysis and Visualizations

- Computed descriptive statistics (mean, median, variance, etc.) for each indicator. 📉
- Aggregated yearly averages by country. 🌍
- Visualized trends from 2019 to 2023 using line charts for each economic indicator. 📅

### 📉 Line Chart Example: Economic Indicators (2019–2023)

- Created a correlation heatmap to identify relationships between indicators. 🔥

### 🔥 Correlation Heatmap

- Produced bar charts showing yearly GDP growth rates by country from 2010 to 2023. 📊

### 📊 Bar Chart: Yearly Average GDP Growth Rate by Country (2010–2023)


## 💡 Key Insights

- Economic indicators vary significantly by country and year. 🌐
- Positive correlations observed, such as between GDP growth and lower unemployment. 📈🤝
- Inflation and interest rates show complex relationships depending on the country. 💸🔄
- Visualizations help identify periods of economic stability and volatility. ⚖️📉📈


## 💾 Output Files

- `cleaned_dataset.csv` — the cleaned data ready for further analysis. 🧹
- `performance_metrics.csv` — aggregated yearly metrics by country. 📅

## 🛠️ Tools Used

- Python (Pandas, NumPy) 🐍
- Visualization libraries (Matplotlib, Seaborn) 🎨

## 🚀 How to Use

1. Load and preprocess the dataset. 📥
2. Explore summary statistics and correlations. 🔍
3. Use visualizations to analyze trends and relationships. 📊
4. Export clean data and aggregated metrics for reporting or further study. 💾



