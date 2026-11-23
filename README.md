# Greedy Uber Eats – Data Analysis

**Project Overview**

A business-focused data analysis project using Microsoft Excel to explore food delivery operations and identify business opportunities.

**Business Problem:** Where should we open our next restaurant?

**Tool:** Microsoft Excel

## Raw Dataset

We received an original raw dataset from Greedy Uber Eats containing food delivery order records.

This dataset serves as the foundation of our project and will be used for data cleaning, exploration, analysis, and business decision-making.

## Phase 2: Data Understanding & Cleaning

The raw dataset was inspected and cleaned using Microsoft Excel.

### Dataset Overview
- 100,000 records
- 36 columns
- 12 cities
- 36 areas
- 29 restaurants

### Data Quality Checks & Cleaning

1. **Duplicate Check:** No duplicate Order IDs or exact duplicate rows found.
2. **Missing Values:** Identified 24,629 missing customer ratings and 57,267 missing promo codes. Both were preserved.
3. **Date Formatting:** Standardized mixed date storage into Excel date values.
4. **Text Validation:** Checked unnecessary leading and trailing spaces.
5. **Numerical Validation:** Checked prices, quantities, customer ages and ratings.
6. **Financial Validation:** Verified Gross Value, Final Order Value and related calculations.
7. **Outlier Investigation:** Suspicious values were retained for further business analysis.

### Cleaning Summary
- No records deleted.
- No missing values artificially filled.
- Negative estimated profits preserved.
- Cancelled orders preserved.
- Original raw dataset kept unchanged.

### Output
The cleaned dataset was saved separately:

`data/cleaned/cleaned_greedy_uber_eats_data.xlsx`

A separate `Data_Cleaning_Report` sheet was also added to document the validation results.