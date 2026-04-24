
📌 Overview

This project performs Exploratory Data Analysis (EDA) on a global layoffs dataset using SQL.
It focuses on identifying trends across companies, industries, countries, and time.

📁 Dataset

The dataset includes the following columns:

Company
Industry
Country
Total Laid Off
Percentage Laid Off
Date

🎯 Objectives
Understand layoff trends over time
Identify the most affected companies and industries
Analyze layoffs distribution by country
Detect patterns using advanced SQL techniques

🔍 Key Insights
📈 2022 recorded the highest number of layoffs
🏢 Top companies: Amazon, Google, Meta
🌍 Most affected countries: United States, India, Netherlands
🏭 Least affected industries: Manufacturing, Energy, Aerospace
🛒 Most affected industries: Consumer, Retail, Transportation

🧠 Analysis Steps

1. Data Exploration
Viewed full dataset
Identified min/max layoffs
Filtered companies with 100% layoffs

2. Aggregations
Total layoffs by company
Total layoffs by industry
Total layoffs by country

4. Time Analysis
Layoffs per year
Monthly layoffs trends
Dataset date range (2020–2023)

6. Advanced Analysis
Rolling totals using window functions
Ranking companies per year using DENSE_RANK()
Using CTEs for structured queries
