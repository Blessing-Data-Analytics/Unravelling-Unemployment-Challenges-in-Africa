# Unravelling-Unemployment-Challenges-in-Africa
A Research analysis exploring unemployment and education data across six African countries to investigate patterns and differences.

## Project Overview
Unemployment is not driven by a single factor. This project examines unemployment across **53 African countries using 2015 observations**, with a focus on gender disparities and selected socioeconomic indicators.

The analysis explores:
- Overall unemployment and country-level differences
- Female vs. male unemployment and the gender gap
- Education spending as a share of government expenditure
- Access to electricity
- Business density / formal business activity as an additional socioeconomic indicator
- Country-level patterns that can inform employment policy and economic development discussions

The goal was not simply to build charts, but to move from **data - evidence - interpretation - recommendations**.

---

## Business Questions

1. Which African countries recorded the highest and lowest average unemployment in the 2015 dataset?
2. How large was the femaleâ€“male unemployment gap?
3. Is higher government spending on education associated with lower unemployment?
4. Is greater access to electricity associated with unemployment levels?
5. What patterns appear between unemployment and formal business activity?
6. Which countries may require different policy responses based on their unemployment and socioeconomic profiles?

---

## Key Findings

### 1. Unemployment varied substantially across countries

Across the 53-country African sample:

- Average unemployment was approximately **9.68%**
- Female unemployment averaged **11.22%**
- Male unemployment averaged **8.15%**
- The average femaleâ€“male unemployment gap was approximately **3.07 percentage points**

The highest average unemployment rates in the dataset included:

- Djibouti - **29.69%**
- South Africa - **25.39%**
- Lesotho - **23.98%**
- Eswatini- **23.38%**
- Gabon - **21.91%**

The lowest included Niger, Chad, Rwanda, Burundi and Madagascar.

> Important: these figures describe the dataset's 2015 observations and should not be interpreted as current unemployment rates.

### 2. Gender disparity was a major pattern

Female unemployment was higher than male unemployment in many countries. The project therefore treats gender as a core analytical dimension rather than presenting only an overall unemployment average.

The relationship between the gender gap and overall unemployment was strong in this sample, with a correlation of approximately **0.73**. This is an association, not proof that one variable causes the other.

### 3. Education spending showed a weak negative association

Education spending as a percentage of government expenditure had a correlation of approximately **-0.24** with average unemployment in the 53-country sample.

This suggests that higher education spending was **not strongly associated with lower unemployment in this cross-sectional dataset**.

A key limitation is that education spending is an input, while unemployment can be influenced by many other factors such as economic structure, labour-market policy, skills mismatch, industrial activity and demographic conditions.

### 4. Electricity access had a stronger positive association

Electricity access had a correlation of approximately **0.52** with unemployment in the sample.

This should **not** be interpreted as electricity access causing higher unemployment. More developed economies may simultaneously have high electricity access and higher measured unemployment because of differences in labour-market participation, urbanization, formal employment and statistical measurement.

This is a good example of why correlation needs business and economic context.

---

## Methodology

### 1. Data preparation

The workbook combines unemployment data with socioeconomic indicators from multiple datasets.

The workflow included:

- Reviewing source tables and schemas
- Cleaning country and country-code fields
- Filtering observations to the 2015 African-country analysis
- Standardizing variables
- Calculating average unemployment
- Calculating the femaleâ€“male unemployment gap
- Combining datasets using country codes
- Creating categorical strategy labels for selected indicators
- Building analysis tables for comparison and visualization

### 2. Analysis

The analysis used:

- Descriptive statistics
- Country ranking
- Gender comparison
- Correlation analysis
- Group comparisons
- Cross-indicator comparisons
- Pivot tables
- Charts and dashboard-style visualizations

### 3. Tools

- **Microsoft Excel**
- **Power Query**
- Pivot Tables
- Excel formulas
- Data cleaning and transformation
- Data visualization

---

## Dashboard 
The dashboard focuses on:

- Average unemployment
- Female vs. male unemployment
- Gender gap
- Country-level unemployment comparisons

<img width="7130" height="5861" alt="Github" src="https://github.com/user-attachments/assets/53dc7d3d-ada0-4bfc-affd-773bc0d40a7d" />

---

## Data Quality & Limitations

This project contains an important data-quality lesson.

One intermediate merged worksheet in the original workbook contains approximately **1.05 million rows but only 55 unique rows**, indicating that the merge created extensive duplicated records.

The final analysis tables used for the country-level comparisons contain 53 unique African-country observations, which is the appropriate grain for the 2015 cross-sectional analysis.

Other limitations include:

- The analysis is based primarily on **2015 observations**, so it does not show how unemployment changed over time.
- Correlation does not establish causation.
- Education spending is measured as a share of government expenditure rather than as spending per student or spending relative to GDP.
- Electricity access is an infrastructure indicator, not a direct measure of job creation.
- Country-level unemployment statistics may reflect differences in labour-force participation and statistical definitions.
- The business-density analysis is constrained by availability and coverage of the underlying data.

These limitations are important when translating the findings into policy recommendations.

---

## Recommendations

### 1. Treat youth and female employment as separate policy problems

The gender gap suggests that employment interventions should not assume that the same factors affect men and women equally.

### 2. Link education investment to labour-market outcomes

Education spending should be evaluated alongside graduate employability, technical skills, vocational training and employer demand rather than treated as an outcome by itself.

### 3. Strengthen the connection between infrastructure and productive employment

Electricity access should be considered alongside industrial activity, business creation and access to productive technology.

### 4. Expand formal employment opportunities

Countries with high unemployment should investigate barriers to business creation, business survival and formal-sector employment rather than focusing only on job-seeker interventions.

### 5. Use more recent longitudinal data

A stronger follow-up analysis should compare multiple years and investigate how unemployment changes alongside industrialization, urbanization, education, electricity access and business activity.

---
