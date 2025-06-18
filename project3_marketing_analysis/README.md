#  Online Game Store Marketing Analysis: Data-Driven Insights for Global Strategy

##  Project Overview
This project analyzes historical sales data from a global online game store to identify which **platforms**, **genres**, and **game titles** are most profitable. Through exploratory data analysis and strategic segmentation, it delivers insights to guide marketing, inventory, and product planning across North America, Europe, and Japan.

---

##  Objective
The goal was to forecast which game genres and platforms are likely to perform best in the global marketplace. By analyzing trends in sales, platform life cycles, regional preferences, and review scores, the project supports data-informed business decisions in the gaming industry.

---

##  What Was Done (Methodology & Techniques)

- **Data Cleaning & Preprocessing**:
  - Removed placeholder values (e.g., "TBD") in review columns.
  - Handled missing values in `year_of_release`, `user_score`, `critic_score`, and `rating`.
  - Converted data types and standardized column names.

- **Platform Lifecycle Analysis**:
  - Evaluated sales trends over time to identify the life span of popular platforms like PS3, X360, Wii, PS4, and XOne.
  - Found that platforms typically have ~10-year lifespans.

- **Genre Performance Evaluation**:
  - Identified Action, Sports, and Shooter as top global genres.
  - Puzzle, Fighting, and Strategy showed lower performance due to limited replay value.

- **Regional Sales Segmentation**:
  - North America: prefers Action, Shooter, Sports (dominant sales region).
  - Europe: similar preferences with additional interest in Racing games.
  - Japan: favors RPGs and handheld platforms like DS.

- **Review Score Impact**:
  - Critic scores had a strong positive correlation with sales.
  - User scores had a weaker correlation, suggesting critic reviews are more predictive of commercial success.

---

##  Visual Example

![Review Score vs Sales](images/game_sales_reviews_heatmap.png)

*Figure: Heatmap showing correlation between review scores and game sales performance across regions.*

---

##  Conclusion

The analysis confirms that **platform choice, genre alignment, and critic review scores** play a significant role in game profitability. These insights can support:
- Platform prioritization
- Genre-focused product development
- Region-specific marketing strategies

---

##  Business Value & Future Strategy

### Business Applications:
- 🎯 Personalize marketing campaigns by region and genre preferences.
- 📦 Align inventory and promotion efforts with platform lifecycles.
- 🤝 Inform influencer partnerships based on review-driven engagement.

### Future Recommendations:
- Incorporate live review feeds and current market data for real-time forecasting.
- Expand to mobile and indie game segments.
- Build an interactive dashboard for internal business use.

---

##  Repository Structure

├── IntegratedProject1.ipynb # Jupyter notebook with all analysis
├── data / # Cleaned dataset and original raw files
├── images/ # Visualizations used in README
│ └── game_sales_reviews_heatmap.png # Example correlation heatmap
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

##  Technologies Used

- **Python**, **pandas**, **NumPy**
- **matplotlib**, **seaborn**
- **Jupyter Notebook**

---

##  Contact

Created by **Sabrina McField**  
📧 sabrinamcfield@gmail.com | [LinkedIn](https://www.linkedin.com/in/sabrinamcfield)

---
