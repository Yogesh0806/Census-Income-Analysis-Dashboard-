# Census Income Analysis Dashboard

## Overview

The Census Income Analysis Dashboard is an interactive Power BI project designed to analyze demographic, educational, and occupational factors that influence annual income levels. Using the Adult Census Income dataset containing 48,842 records, the dashboard provides insights into income distribution, workforce characteristics, and socioeconomic patterns.

The project leverages Power BI, Power Query, and DAX to transform raw census data into meaningful business intelligence through interactive visualizations and KPI-driven analysis.

---

## Business Problem

Understanding the factors that influence income levels is essential for policymakers, researchers, workforce analysts, and organizations. Traditional tabular data makes it difficult to identify patterns and relationships between demographic characteristics and income categories.

This dashboard addresses that challenge by providing an interactive analytical solution that highlights the key drivers of income and enables users to explore trends across multiple demographic dimensions.

---

## Project Objectives

* Analyze income distribution across the population.
* Identify demographic factors associated with higher income levels.
* Evaluate the impact of education on income.
* Explore occupational and workforce trends.
* Monitor key performance indicators related to income categories.
* Enable interactive analysis through filters and slicers.
* Support data-driven decision-making through visual insights.

---

## Dataset Information

| Metric            | Value                           |
| ----------------- | ------------------------------- |
| Dataset Name      | Adult Census Income Dataset     |
| Records           | 48,842                          |
| Features          | 15                              |
| Source            | UCI Adult Census Income Dataset |
| Data Type         | Structured Tabular Data         |
| Income Categories | <=50K and >50K                  |

### Features Included

* Age
* Workclass
* Final Weight (fnlwgt)
* Education
* Educational Number
* Marital Status
* Occupation
* Relationship
* Race
* Gender
* Capital Gain
* Capital Loss
* Hours Per Week
* Native Country
* Income

---

## Tools and Technologies

* Power BI
* Power Query
* DAX
* CSV Dataset
* Data Modeling
* Data Visualization
* Business Intelligence

---

## Data Cleaning and Transformation

The following data preparation steps were performed:

* Removed unnecessary inconsistencies.
* Handled missing categorical values represented as "?".
* Verified data types for all fields.
* Created calculated measures using DAX.
* Organized fields into dimensions and measures.
* Optimized the dataset for dashboard reporting.
* Validated income classifications and category labels.

---

## Dashboard Features

### Executive Dashboard

Provides a high-level overview of the dataset through KPI cards and summary visualizations.

Key Metrics:

* Total Population
* High Income Population
* Low Income Population
* Average Age
* Average Working Hours

### Demographic and Workforce Analysis

Analyzes population characteristics including:

* Age Distribution
* Gender Analysis
* Education Levels
* Marital Status
* Occupational Segmentation

### Income Drivers Analysis

Focuses on factors influencing income classification:

* Education vs Income
* Occupation vs Income
* Gender vs Income
* Working Hours vs Income
* Capital Gain Impact

---

## KPIs Tracked

| KPI                     | Description                                  |
| ----------------------- | -------------------------------------------- |
| Total Population        | Total number of individuals in the dataset   |
| High Income Population  | Individuals earning more than $50K           |
| Low Income Population   | Individuals earning $50K or less             |
| High Income Percentage  | Percentage of individuals earning above $50K |
| Average Age             | Average age of the population                |
| Average Working Hours   | Average weekly working hours                 |
| Male High Income Rate   | Percentage of males earning above $50K       |
| Female High Income Rate | Percentage of females earning above $50K     |

---

## Dashboard Preview

### Overview Dashboard

![Dashboard Overview](Images/dashboard_overview.png)

### Demographic Analysis

![Demographic Analysis](Images/demographic_workforce_analysis.png)

### Income Drivers Analysis

![Income Drivers Analysis](Images/income_drivers_advanced_analytics.png)

---

## Key Insights

1. Only 23.93% of individuals earn more than $50K annually.
2. More than 76% of the population falls into the lower-income category.
3. Male individuals have a significantly higher probability of earning above $50K compared to females.
4. Higher education levels are strongly associated with higher income.
5. Professional School graduates exhibit one of the highest high-income rates.
6. Doctorate holders consistently demonstrate strong earning potential.
7. Capital gain is a significant indicator of higher income levels.
8. Occupation plays a major role in income classification.
9. Working more hours per week generally correlates with higher income.
10. Marital status shows a measurable relationship with income outcomes.

---

## Business Recommendations

* Invest in education and skill development programs.
* Focus workforce initiatives on high-demand occupations.
* Use demographic segmentation for targeted policy planning.
* Promote career advancement opportunities for lower-income groups.
* Leverage income trend analysis for socioeconomic research and planning.

---

## Project Impact

This dashboard transforms raw census data into actionable business intelligence. It enables users to identify income patterns, understand workforce dynamics, and evaluate demographic influences on earning potential. The interactive reporting experience supports faster and more informed decision-making.


---

## How to Use

1. Clone the repository.
2. Open the Power BI (.pbix) file.
3. Refresh the dataset if required.
4. Interact with slicers and filters.
5. Explore dashboard pages and insights.

---

## Future Improvements

* Add predictive income analysis using machine learning.
* Incorporate geographic income mapping.
* Build drill-through reporting pages.
* Add advanced DAX calculations.
* Integrate real-time demographic datasets.

---

## Author

**Yogesh Yadav**

Aspiring Data Analyst | Power BI Developer | Data Science Student

### Connect With Me

* GitHub: https://github.com/Yogesh0806
* LinkedIn: https://www.linkedin.com/in/yogesh-yadav-b0b457330/

---

### Project Highlights

* 48,842 Census Records Analyzed
* 15 Features Evaluated
* Interactive Power BI Dashboard
* DAX-Based KPI Tracking
* Workforce and Income Analysis
* Data-Driven Business Insights
