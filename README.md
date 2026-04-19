# ATM Usage Pattern Analysis

## Problem Statement
Analyse the withdrawal behaviour of ATM users to identify usage patterns across different time periods, locations, and contextual factors.

## Dataset
- **File:** `atm_cash_management_dataset.csv`
- **Records:** 5,658 rows × 13 columns
- **Date Range:** January 2022 – January 2024
- **Features include:** ATM ID, Date, Day of Week, Time of Day, Total Withdrawals, Location Type, Weather Condition, Holiday Flag, and more.

## Key Tasks
- **Data Cleaning:** Checked for null values, duplicates, and data types. Converted date column to datetime format.
- **Grouping:** Grouped withdrawal data by Day of Week, Time of Day, Location Type, and Weather Condition.

## Visualizations
- Bar plot — Average Withdrawals by Day of Week
- Line plot — Monthly Withdrawal Trend (2022–2024)
- Bar plot — Average Withdrawals by Location Type
- Bar plot — Average Withdrawals by Time of Day

## Key Findings
- Monday records the lowest withdrawals; Tuesday is the highest.
- No strong seasonal trend observed — demand stays stable between 47,000 and 52,000.
- Morning is the peak time slot for ATM usage.
- Bank Branch ATMs handle the most withdrawals; Mall ATMs the least.
  

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)
