# Project Background
Gamezone is a global e-commerce retailer specializing in gaming hardware and consoles, selling directly to consumers across multiple regions. Between 2019 and early 2021, the company experienced significant volatility in demand, creating uncertainty around product performance, marketing effectiveness, and regional sales trends. 

Despite collecting detailed transaction-level data on sales, products, marketing channels, and regions, this data had not been fully leveraged to understand the drivers behind revenue growth and decline. This project thoroughly analyzes and synthesizes this data to identify trends driving revenue growth and decline and uncover actionable insights that will improve Gamezone's commercial success. 

Insights and recommendations are provided on the following key areas:

- **Sales Trends Over Time:** Analysis of monthly revenue, order volume, and average order value to identify patterns and to inform revenue forecasting.  
- **Product Performance:** Evaluation of individual product lines to understand top performers, underperforming products, and the drivers behind revenue changes. 
- **Marketing Channel Impact:** Assessment of marketing channel effectiveness (direct, email, social media, etc) on sales trends, highlighting opportunities to optimize marketing spend and improve ROI. 
- **Regional Performance:** Evaluation of revenue trends by region to identify geographic strengths and weaknesses and to inform regional sales strategies.  


An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

Before analysis, the dataset was reviewed to understand its structure, data types, and key fields relevant to business performance. Initial quality checks were conducted in Excel to confirm consistent date formats, valid revenue values, and complete product, region, and marketing classifications. 

| Column Name       | Data Type | Description                                 |
|------------------|-----------|---------------------------------------------|
| Order ID          | string    | Unique identifier for each order            |
| Product Name      | string    | Name of the purchased product               |
| Purchase Date     | date      | Date the order was placed                    |
| USD Price         | float     | Revenue from each order                      |
| Marketing Channel | string    | Channel through which order originated      |
| Region            | string    | Geographic region of the customer           |



# Executive Summary

### Overview of Findings

Between 2019 and early 2021, the company experienced rapid revenue growth followed by a sharp **55% decline** in early 2021. While this downturn broadly aligns with post-pandemic demand normalization, deeper analysis reveals that the decline was disproportionately driven by **three core products**. The Sony PlayStation, Gaming Monitor, and Nintendo Switch accounted for **80% of total revenue**, while the **direct marketing channel** was responsible for **85% of revenue**. Regional analysis shows the downturn was global in nature, with **North America contributing 54% of total revenue losses**, especially in PlayStation sales. The following analysis explores these patterns in detail and highlights key opportunities to stabilize revenue and optimize channel and product strategy. 



# Insights Deep Dive
### Sales Trends:

* **Revenue peaked in December 2020  following sustained growth since 2018, then declined ~~55% by February 2021.** This drop reflects demand normalization after elevated pandemic-era holiday sales.
  
* **Peak-to-trough analysis identifies periods of heightened revenue risk.** The sharp December-February swing highlights when the company is most vulnerable to demand volatility, which informs timing for forecasting and cash flow planning. 
  
* **Short-term volatility masked underlying demand resilience.** Despite the early 2021 drop, monthly revenue remained above pre-pandemic 2019 levels, showing that baseline demand remained strong. 

![Sales Trends](gamezone_chart1.PNG)

### Product Performance:

* **Revenue was heavily concentrated in three core products.** The Sony PlayStation, Gaming Monitor, and Nintendo Switch collectively accounted for **80% of total revenue**, making them the primary drivers of growth and decline. PlayStation experienced the steepest drop, falling from $167K → $63K, while Switch and Monitor declined less sharply.  
  
* **Minor products contributed minimally but highlight opportunities.** Products, like the Headset, accounting for <2% of revenue, could be bundled or promoted to diversify revenue streams and reduce concentration risk.  
  
* **Relative product contribution to decline varies by product.** PlayStation alone accounted for ~35% of the total revenue drop, highlighting the company’s exposure to high-impact product performance.

![Product Performance](gamezone_chart2.PNG)

### Marketing Channel Analysis:

* **Direct channel dominates revenue** Approximately **85% of sales** occurred through Direct marketing channels, highlighting the impact of changes in consumer behavior. 
  
* **Product-level declines were driven by heavy reliance on Direct marketing channels.** All three top products experienced sharp revenue drops, but the impact was most pronounced for the PlayStation, which fell **64%** in Direct channel sales alone, highlighting channel-specific vulnerability. 
  
* **Underutilized channels present opportunities for growth.** Minimal contribution from email, affiliate, and social media channels indicates untapped potential to diversify revenue streams and mitigate risk. 

![Marketing Channel Analysis](gamezone_chart3.PNG)


### Regional Trends:

* **Revenue declines were global, but NA drove the majority of losses.** Between December 2020 and February 2021, all regions experienced downturns, but NA accounted for **54% of total revenue loss**, making it the primary contributor to the overall contraction.

* **Top product declines were amplified by regional concentration.** All top three products fell sharply in NA, with PlayStation revenue declining by over **66%** during the period. Similar directional trends across products suggest the downturn was broad-based rather than product-specific. 
  
* **Geographic diversification could stabilize revenue.** Reliance on NA revenue for top products exposes the company to regional market shifts; expanding sales in Europe or APAC could mitigate future risk.

![Regional Trends](gamezone_chart4.PNG)



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
