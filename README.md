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

1. The United States, Mexico, and Germany are predicted to remain the most visited countries in 2024, reflecting consistent tourism demand.
2. Most top countries show a strong growth trend from 2022 to 2024, suggesting a recovery in international travel post-pandemic.
3. Some countries like Egypt show fluctuations in arrivals across years, indicating sensitivity to regional or global events.

## Visualizations

1. **Top 10 Countries by Predicted Arrivals 2024**
2. **Trend of International Arrivals for Top 5 Countries 2022-2024**

## Tools Used

* Python
* pandas
* matplotlib
* seaborn

---
