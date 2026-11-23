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


## Phase 4: Business Insights & Opportunity Identification

Analysed city-wise and area-wise demand, revenue, cuisine preferences, and order statuses using Microsoft Excel Pivot Tables.

### Analysis Performed

- Identified the Top 5 cities based on order volume.
- Identified the Top 5 areas based on order volume.
- Analysed the Top 5 popular cuisines.
- Compared order statuses across cities.
- Identified the Top 5 cities by revenue.
- Compared demand and revenue across Mumbai areas.

### Key Business Insights

**1. City-wise Demand**
- Mumbai ranked first with 8,564 orders.
- Lucknow ranked second with 8,390 orders.
- Greater Noida ranked third with 8,360 orders.

**2. Cuisine Preferences**
- North Indian was the most ordered cuisine with 17,209 orders.
- Biryani ranked second with 10,568 orders.

**3. Order Status**
- Delivered: 91,976
- Cancelled: 4,927
- Refunded: 3,097

**4. Mumbai Area Analysis**

| Area | Orders | Revenue (INR) |
|---|---:|---:|
| Powai | 2,902 | 1,466,769.35 |
| Andheri | 2,866 | 1,494,103.54 |
| Bandra | 2,796 | 1,437,522.02 |

### Business Findings

- Mumbai recorded the highest overall order demand.
- Powai had the highest order volume among the three analysed Mumbai areas.
- Andheri generated the highest revenue among these areas.
- Demand and revenue rankings were different, showing why both metrics matter in location selection.

### Tools Used
- Microsoft Excel
- Pivot Tables
- Value Filters
- Sorting and Aggregation

### Final Outcome

Identified Mumbai as a leading city for further investigation. Powai and Andheri emerged as potential areas for further evaluation.

A final restaurant location decision requires additional analysis .

**Output:** Business Insights Pivot Tables and analysis screenshots.


## Phase 5: Profitability Analysis & Final Business Recommendation

Compared the financial performance of Mumbai's three areas: Andheri, Powai, and Bandra using Microsoft Excel Pivot Tables.

### Analysis Performed

- Compared estimated profit across Mumbai areas.
- Compared estimated operational costs.
- Analysed area-wise revenue.
- Calculated cancellation rates.
- Compared customer demand and financial performance.

### Profitability Comparison

| Area | Estimated Profit (INR) | Estimated Cost (INR) |
|---|---:|---:|
| Andheri | 297,632.94 | 196,086.90 |
| Powai | 287,286.85 | 198,046.70 |
| Bandra | 284,438.79 | 190,391.81 |

### Cancellation Rate Analysis

| Area | Cancelled Orders | Total Orders | Cancellation Rate |
|---|---:|---:|---:|
| Andheri | 144 | 2,866 | 5.02% |
| Powai | 167 | 2,902 | 5.75% |
| Bandra | 128 | 2,796 | 4.58% |

**Formula:**

Cancellation Rate = (Cancelled Orders / Total Orders) × 100

### Key Business Insights

- Andheri generated the highest revenue among the three areas.
- Andheri recorded the highest estimated profit of ₹2,97,632.94.
- Powai recorded the highest order demand with 2,902 orders.
- Andheri had a lower cancellation rate than Powai.
- Bandra recorded the lowest cancellation rate at 4.58%.

### Final Business Recommendation

**Recommended Location: Andheri, Mumbai**

Based on the available dataset, Andheri is the strongest candidate for the next restaurant because it recorded the highest revenue and estimated profit among the three analysed areas.

Powai also represents a potential opportunity because of its higher order volume.

This recommendation is based on historical order and financial data. Actual investment decisions should also consider rent, competition, and future operating expenses.

### Tools Used
- Microsoft Excel
- Pivot Tables
- Financial Analysis
- Percentage Calculations
- Business Decision-Making

**Project Outcome:** Identified Andheri, Mumbai as the leading candidate for the next restaurant location based on the available data.

