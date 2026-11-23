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

## Phase 3: Demand Analysis

Analysed customer demand across different cities, areas, cuisines, meal periods, months, and weekdays using Microsoft Excel Pivot Tables.

### Analysis Performed

Created six Pivot Tables to understand demand patterns:

1. **City-wise Demand:** Compared total orders across cities.
2. **Area-wise Demand:** Identified areas with the highest order volume.
3. **Cuisine-wise Demand:** Analysed customer preferences across cuisines.
4. **Meal Period Demand:** Compared orders across different meal periods.
5. **Monthly Demand Trend:** Examined changes in order demand over time.
6. **Weekend vs Weekday Demand:** Compared customer ordering patterns.

### Key Observations

- Mumbai recorded the highest city-wise demand with 8,564 orders.
- Lucknow ranked second with 8,390 orders.
- Greater Noida ranked third with 8,360 orders.
- All Pivot Tables were sorted in descending order to identify high-demand categories easily.

### Tools Used
- Microsoft Excel
- Pivot Tables
- Data Sorting

### Analysis Output

Screenshots of all six Pivot Tables are available in the `Demand Analysis/` folder.

**Output:** Demand Analysis screenshots (`Analysis` folder).
