# Exploratory Data Analysis & Visualization - Online Game Store Marketing Analysis

This project analyzes historical sales data from a global online game store to identify which platforms, genres, and games are most likely to be profitable in Ice's global marketplace. By breaking down platform life cycles, regional preferences, and review impacts, we offer actionable insights to guide future marketing and product strategies.

## Objective
To forecast which **game genres**, **platforms**, and **titles** will be the most profitable based on historical trends, regional behavior, and review scores.

## Key Features

- **Data Cleaning & Preparation**: Standardized column formats, removed TBD values from `user_score`, and handled missing values in key fields like `critic_score`, `user_score`, `year_of_release`, and `rating`.

- **Platform Lifecycle Analysis**: Grouped game sales by platform and year to evaluate platform popularity and lifecycle trends (e.g., ~10-year life spans for PS3, Wii, X360).

- **Genre & Regional Sales Trends**: Analyzed total and regional sales by genre to identify top-performing categories (Action, Sports, Shooter) and regional preferences (e.g., RPGs in Japan, Racing in Europe).

- **Correlation & Review Impact**: Compared critic and user scores to game sales, finding a strong correlation between critic scores and commercial success.

- **Visualization & EDA**: Included numerous visualizations to support analysis of release patterns, sales distribution, and performance by ESRB rating.

## Technologies Used
- Python
- pandas, seaborn, matplotlib
- Jupyter Notebook

## Outcome
This analysis equips stakeholders with insights to:
- Prioritize platform investments
- Forecast regional demand
- Align marketing with review-based predictors
- Guide genre-specific promotional efforts

