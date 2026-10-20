# Analysis of Indian Mutual Fund Industry Using Python

## Project Overview

This project focuses on analysing the Indian mutual fund industry using the AMFI Monthly Report dataset obtained from the India Data Portal. Python was used to clean the data, perform statistical analysis, explore trends, and create visualizations to understand mutual fund performance over time.

## Objectives

- To inspect and understand the AMFI mutual fund dataset.
- To identify and handle missing values, duplicate records, outliers, and data-format issues.
- To perform exploratory data analysis (EDA).
- To analyse numerical and categorical variables.
- To study yearly trends in Net Assets Under Management (Net AUM) and net inflow/outflow.
- To examine relationships between numerical variables using correlation analysis.
- To create univariate, bivariate, and multivariate visualizations.
- To derive meaningful insights from the dataset.

## Dataset

**Dataset Name:** AMFI Monthly Report

**Source:** India Data Portal

**Dataset Link:** https://indiadataportal.com/p/investments/r/amfi-amfi_monthly_report-in-mn-aaa

The dataset contains information related to mutual fund schemes, including:

- Scheme Name
- Scheme Type
- Scheme Category
- Number of Schemes
- Number of Folios
- Fund Mobilized
- Repurchase and Redemption
- Net Inflow/Outflow
- Net Assets Under Management (Net AUM)
- Average Net AUM
- Segregated Portfolio Information

The dataset covers monthly observations across multiple years.

## Tools and Technologies

- **Python** – Data analysis and processing
- **Google Colab** – Coding environment
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Plotly Express** – Interactive visualizations

## Project Workflow

1. **Data Loading and Inspection:** Loaded the dataset and examined its structure, columns, data types, and sample records.
2. **Data Cleaning:** Identified and handled data-quality issues, including duplicate records, missing values, and date-format inconsistencies.
3. **Outlier Detection:** Used the Interquartile Range (IQR) method to identify potential outliers and reviewed them before deciding how to handle them.
4. **Feature Engineering:** Extracted year and month from the date column for time-based analysis.
5. **Statistical Analysis:** Performed descriptive statistical analysis, categorical analysis, numerical analysis, and correlation analysis.
6. **Data Visualization:** Created univariate, bivariate, and multivariate visualizations to explore distributions, relationships, and trends.
7. **Interactive Visualization:** Used Plotly Express to create interactive visualizations.

## Visualizations

The project includes visualizations such as:

- Distribution of Net AUM using a histogram
- Net AUM boxplot for outlier analysis
- Distribution of scheme types
- Scheme category comparison
- Relationship between Net AUM and fund mobilized 
- Yearly average net inflow/outflow trend
- Net AUM comparison across scheme types
- Multivariate analysis using a pair plot
- Interactive yearly Net AUM trend
- Interactive correlation heatmap

## Key Findings

- The yearly average Net AUM showed an overall increasing trend from 2019 to 2024.
- Open-ended schemes recorded a higher average Net AUM than close-ended and interval schemes in the analysed dataset.
- Fund mobilized and repurchase/redemption showed a very strong positive correlation.
- The correlation analysis helped identify relationships among selected numerical variables.
- The visualizations provided a clearer understanding of trends, distributions, and differences across scheme types and categories.

## Conclusion

This project demonstrates how Python can be used to clean, analyse, and visualize mutual fund data. The analysis helped identify important trends and relationships in the AMFI Monthly Report dataset and provided practical experience in data cleaning, statistical analysis, exploratory data analysis, and visualization.

## Limitations and Future Scope

- The analysis is limited to the available dataset and its covered period.
- Missing values and outliers require careful interpretation based on the context of the data.
- Future work could include analysing additional financial indicators, comparing more recent data, and developing predictive models.

## References

- India Data Portal – AMFI Monthly Report: https://indiadataportal.com/p/investments/r/amfi-amfi_monthly_report-in-mn-aaa
- Google Colab: https://colab.research.google.com/
