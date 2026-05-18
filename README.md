# MIS311_Portfolio_Chau-Hoang-Huy

## Overview

This project analyzes the Most Visited Countries dataset to uncover trends in international tourist arrivals. The dataset includes historical data from 2022-2023 and predictive estimates for 2024, helping to understand which countries attract the most tourists and how arrivals have changed over time.

## Dataset Details

* **Source:** Provided for MIS 311 assignment.
* **Number of Rows:** [Insert number of countries]
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
* **most_visited_countries.xlsx** – dataset
* **images/** – folder containing visualizations:

  * `top10_predicted_2024.png`
  * `top5_trend_2022_2024.png`

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
   ![Top 10 Predicted 2024](images/top10_predicted_2024.png)
2. **Trend of International Arrivals for Top 5 Countries 2022-2024**
   ![Top 5 Trend 2022-2024](images/top5_trend_2022_2024.png)

## Tools Used

* Python
* pandas
* matplotlib
* seaborn

---

**Author:** Chau Hoang Huy
**IRN:** 2032300074
**GitHub Portfolio Link:** [https://github.com/huychaubbs20-tech](https://github.com/huychaubbs20-tech)


