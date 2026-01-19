# 📊 Sleep_DataAnalysis
This repository contains a Python-based data analysis project focused on cleaning, transforming, and analyzing sleep-related time-series data using pandas, NumPy, regex, and matplotlib
# 🔍 Project Overview
The workflow begins by importing raw CSV data from a public GitHub source, cleaning irrelevant text rows, and isolating sleep-related records into a new DataFrame. The dataset is then progressively refined through deduplication, missing-value handling, time normalization, and feature engineering.

# Key transformations include:
Filling and standardizing missing duration values
Converting time strings (HH:MM) into integer minutes
Removing time components from datetime columns to analyze unique days
Calculating averages, minimums, maximums, percentage changes, and derived metrics
The project concludes with statistical analysis, sleep cycle estimation, data coverage calculations, and visualization, producing publication-ready plots saved at high resolution.

# 🧠 Key Features
Data ingestion from remote CSV sources
Robust data cleaning and preprocessing
Regex-based time manipulation
Feature engineering (calculated duration in minutes)
Descriptive statistics (mean, min, max)
Percentage change analysis
Sleep cycle and data coverage estimation
Side-by-side matplotlib visualizations
High-resolution figure export (600 DPI)
# 🛠️ Technologies Used
Python
pandas
NumPy
re (Regular Expressions)
matplotlib

# 📈 Outputs
Cleaned and enriched DataFrame
Calculated sleep duration metrics
Percentage change analysis
Two-panel visualization comparing duration and change
PNG figure saved programmatically for reporting

🎓 Academic Context
This project was completed as part of Artificial Intelligence 5 – AIN580S and demonstrates practical data wrangling, analytical reasoning, and visualization skills using real-world datasets.
