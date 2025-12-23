# Food Order Explatory Data Analysis & Business Optimization

## 📋 Project Overview
FoodHub is a food aggregator that connects New York City residents with various restaurants. This project involves a comprehensive analysis of customer behavior, restaurant performance, and delivery efficiency. The goal is to provide data-driven recommendations to improve customer retention and optimize the company's revenue model.

## 🎯 Business Objective
* **Customer Profiling:** Identify top customers and their ordering patterns to target marketing efforts.
* **Operational Efficiency:** Analyze delivery times and preparation times to reduce total delivery duration.
* **Revenue Optimization:** Evaluate the effectiveness of the current commission structure and suggest improvements.
* **Quality Control:** Investigate the relationship between ratings and restaurant performance.

## 🛠️ Methodology
1. **Data Wrangling:** Cleaned and structured the dataset, handling missing ratings and ensuring correct data types for time-based analysis.
2. **Exploratory Data Analysis (EDA):** Performed univariate and multivariate analysis to identify trends in cuisine popularity, order volume by day of the week, and delivery bottlenecks.
3. **Business Logic Implementation:** Created calculated fields to determine "Total Delivery Time" and "Net Revenue" based on tiered commission structures.
4. **Statistical Summaries:** Generated descriptive statistics to identify high-performing restaurants and regions.

## 🧰 Technical Skills & Tech Stack
* **Analysis:** Python, Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Business Intelligence:** Descriptive Statistics, Revenue Modeling, Operational Analysis

## 📈 Results & Key Insights
* **Peak Performance:** Weekends account for a significantly higher volume of orders, suggesting a need for increased delivery staff during these windows.
* **Cuisine Trends:** American, Japanese, and Italian cuisines dominate the platform, making up over 70% of total orders.
* **Delivery Bottlenecks:** Identified that "Food Preparation Time" is more volatile than "Travel Time," indicating a need for better restaurant-side efficiency.
* **Revenue Potential:** A significant portion of orders falls under a high-revenue tier, suggesting that a small percentage of high-volume restaurants drive the majority of FoodHub's profit.

## 💡 Strategic Recommendations
* **Promotional Strategy:** Introduce loyalty programs for the top 5% of customers who contribute to the bulk of the revenue.
* **Service Standards:** Partner with restaurants showing high preparation times to streamline their kitchen operations for the app.
* **Rating Incentives:** Implement a feedback prompt for unrated orders to improve the data density for restaurant quality scores.
