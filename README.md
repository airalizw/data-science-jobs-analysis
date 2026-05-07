# Data Science Jobs Analysis 💼

## Project Overview
Cleaned and analyzed a dataset of 672 data science job postings scraped from Glassdoor via Kaggle. Identified data quality patterns, handled coded missing values, and built a dashboard to surface insights on hiring trends by sector, industry, and location.

## Tools Used
- Microsoft Excel
- Pivot Tables and Pivot Charts
- Data Cleaning and Validation

## Key Cleaning Finding
This dataset used -1 as a coded placeholder for missing data throughout. Removing duplicates was intentionally skipped as job titles repeat legitimately across different companies.

## Data Cleaning Summary
| Column | Issue | Rows Fixed |
|---|---|---|
| Headquarters | -1 values | 31 |
| Company Size | -1 values | 27 |
| Founded Year | -1 values | 118 |
| Ownership Type | -1 values | 27 |
| Industry | -1 values | 71 |
| Sector | -1 values | 71 |
| Revenue | Unknown and -1 values | 240 |
| Competitors | -1 values | 501 |

## Key Findings
- Information Technology dominates with 188 of 672 job postings
- San Francisco leads all cities with 69 postings followed by New York at 50
- Publishing and Video Games have the highest employee ratings
- Wholesale and Rail have the lowest employee ratings

## Business Insights
Data science job seekers should target IT and Business Services sectors first for maximum opportunity. Geographic concentration in San Francisco and New York suggests remote options are worth prioritizing for candidates outside these markets.
