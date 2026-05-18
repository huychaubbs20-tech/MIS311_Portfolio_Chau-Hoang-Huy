# MIS311 - Assignment #7: Most Visited Countries

## Overview

This project analyzes the Most Visited Countries dataset to uncover trends in international tourist arrivals. The dataset includes historical data from 2022-2023 and predictive estimates for 2024, helping to understand which countries attract the most tourists and how arrivals have changed over time.

## Dataset Details

* **Source:** Provided for MIS 311 assignment.
* **Number of Rows:** 17
* **Number of Columns:** 6
* **Columns:**

  * `Country`: Name of the country
  * `MostVisited_NumOfArrivalsPredictive_Millions_2024`: Predicted arrivals 2024
  * `MostVisited_NumOfArrivals_Millions_2023`: Actual arrivals 2023
  * `MostVisited_NumOfArrivals_Millions_2022`: Actual arrivals 2022
  * `MostVisited_NumofArrivals_WorldBank`: World Bank reported arrivals
  * `MostVisited_DataYear_WorldBank`: Year of World Bank data

## Project Structure

* **README.md** – this file explaining the project
* **07_Most Visited Countries.xlxx** – dataset
* **images** – folder containing visualizations:


## Data Cleaning Summary

| Issue                        | Action Taken                                |
| ---------------------------- | ------------------------------------------- |
| Non-numeric arrival values   | Converted to numeric, errors coerced to NaN |
| Missing values               | Checked, no missing values found            |
| Duplicate countries          | Checked, no duplicates found                |
| Consistency of country names | Verified                                    |

## Key Findings / Insights

Insight 1:
The average predicted arrivals for 2024 is 38.32 million, indicating strong demand for international travel. Countries like the United States and Mexico are outliers with significantly higher values, showing their dominant tourism position.
Insight 2:
Comparing 2022 and 2023 arrivals, the mean growth indicates recovery in global tourism after the pandemic. Some countries show fluctuations, suggesting sensitivity to regional or global events.

## Visualizations

1. **Top 10 Countries by Predicted Arrivals 2024**
2. **Trend of International Arrivals for Top 5 Countries 2022-2024**

## Tools Used

* Python
* pandas
* matplotlib
* seaborn

---
