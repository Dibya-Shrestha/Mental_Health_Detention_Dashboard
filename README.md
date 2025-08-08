📊 Mental Health Detentions Dashboard
Overview
This repository contains an Excel-based dashboard for analysing Mental Health Services Dataset (MHSDS) detention data.
The dashboard provides insights into detention rates, demographic patterns, and organisational performance across NHS Trusts, ICBs, and Independent Health Providers.

The analysis focuses on:
- Ethnic group distribution of detentions
- Organisation breakdown by provider type
- Crude rate distribution and outlier detection
- Section usage patterns by gender
- Age group distribution of total detentions
- Top 10 organisations ranked by crude detention rate

Data Structure
The dataset includes the following key fields:
- Year – Reporting year (e.g., 2023/24)
- Measure – e.g., All detentions
- Demographic Breakdown – Gender, Age, Ethnicity, etc.
- Organisation Breakdown – NHS Trust, ICB, Independent Provider
- Organisation Name (OrgName) – Name of provider or board
- Counts – Total, Acute, and MHSDS submission counts
- Crude Rate – Detention rate per 100,000 population
- Standardised Rate – Adjusted rate (optional)

Dashboard Components
1. Detentions by Ethnic Group – All Submissions
Horizontal bar chart showing total detentions for each ethnic group, highlighting disparities.

2. Organisation Count by Crude Rate Range
Histogram showing the distribution of organisations by crude rate brackets. Useful for spotting overall spread and potential outliers.

3. Section Usage by Gender
100% stacked bar chart showing section usage by gender categories (Male, Female, Non-binary, Other, All genders, Not stated, Missing).

4. Organisation Breakdown Share
Pie chart showing the proportion of detentions reported by:

NHS Trusts

Independent Health Providers

Integrated Care Boards (ICBs)

5. Total Detentions by Age Group (National Level)
Bar chart breaking down detentions across standard age groups (15 and under → 65+).

6. Top 10 Organisations by Crude Rate
Horizontal bar chart showing the organisations with the highest crude detention rates.

Outlier Detection
Outliers are flagged using two complementary methods:
- Percentile Method

High Outliers – Above 95th percentile

Low Outliers – Below 5th percentile

- Median-Based Method

Compares each organisation’s crude rate to the median (P50).

Identifies organisations significantly above or below the median for additional context on data skewness.

## Explore the pivot tables for deeper analysis.

Check Outlier Flag fields to identify organisations outside expected ranges.

