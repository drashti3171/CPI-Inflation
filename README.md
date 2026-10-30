## Consumer Price Index (CPI) Inflation Analysis | India

### Understanding Inflation Trends, Consumer Price Movements & Economic Patterns

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Focus-Data%20Analytics-blue?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-CPI%20Inflation-orange?style=for-the-badge)

## Project Overview

Inflation is one of the most important indicators of an economy's financial health. It directly affects the purchasing power of consumers, household expenditure, and the overall cost of living.

This project focuses on analyzing **Consumer Price Index (CPI) data in India** to understand how prices have changed across different expenditure categories and geographical sectors over time.

Using Microsoft Excel, I performed data cleaning, transformation, classification, pivot-table analysis, trend analysis, and correlation analysis to identify meaningful patterns in inflation.

The project explores inflation trends across Rural, Urban, and Rural + Urban sectors, examines price movements before and after COVID-19, and investigates the relationship between Fuel & Light inflation and other expenditure categories.

## Project Objectives

- Analyze the overall CPI trend across Rural, Urban, and Rural + Urban sectors.
- Understand the contribution and distribution of different expenditure categories in the dataset.
- Examine year-over-year CPI growth and identify periods of higher inflation.
- Analyze monthly price fluctuations in essential food commodities.
- Compare inflation trends before and after the COVID-19 period.
- Investigate the relationship between Fuel & Light inflation and other expenditure categories using correlation analysis.
- Generate meaningful insights to understand consumer price movements and inflationary patterns.

## Tools & Techniques Used

| Tool / Technique | Application |
|---|---|
| Microsoft Excel | Data analysis and visualization |
| Data Cleaning | Formatting and preparing raw CPI data |
| Data Transformation | Converting wide-format data into long/unpivoted format |
| Pivot Tables | Category-wise and sector-wise analysis |
| Percentage Change | Measuring year-over-year and monthly movements |
| Correlation Analysis | Examining relationships between CPI categories |
| Charts & Visualization | Identifying trends and communicating findings |


### 1. Broad Category-Wise Distribution

The unpivoted dataset contains **10,044 classified observations**.


<img width="462" height="284" alt="image" src="https://github.com/user-attachments/assets/4d13e76d-9d87-4eac-a056-b6765a0f464d" />


Key findings:

- Food accounts for **44.44%** of the classified observations.
- Luxury represents 14.81%.
- Clothing represents 11.11%.
- Housing represents 7.41%.
- The remaining categories each account for approximately 3.70%.

**Insight:** Food is the most represented expenditure category in the dataset and deserves significant attention when examining consumer price movements.

### 2. Year-over-Year CPI Analysis

The General CPI Index was analyzed across Rural, Urban, and Rural + Urban sectors from 2016 to 2023.


<img width="518" height="259" alt="image" src="https://github.com/user-attachments/assets/988ccf54-eb2f-4561-b3b0-cde7c730f0d9" />


**Key Insights:**

- CPI increased consistently across all three sectors.
- Rural CPI remained higher than Urban CPI throughout the analyzed period.
- The highest annual growth occurred in 2022.
- Rural inflation growth reached approximately **6.85%** in 2022.
- Inflation growth moderated to around 3% across all sectors in 2023.

### 3. Monthly Commodity-Level Inflation Analysis

The monthly price movements of four essential commodities were examined:


<img width="495" height="223" alt="image" src="https://github.com/user-attachments/assets/2eaf4548-fc7d-4a66-bc83-2e5115b3733d" />

**Key Findings:**

- Vegetables showed the highest price volatility, reaching an index of approximately 204.37 in October 2022.
- Milk demonstrated relatively consistent upward movement.
- Pulses experienced comparatively gradual price increases.
- Fruits showed considerable fluctuations during the analyzed months.

The Rural, Urban, and Rural + Urban comparison from 2022 to 2023 further revealed:

**Insight:** Vegetables were the most volatile category, with changes ranging from -12.7% to 4.2%. Fruits were the second most variable, ranging from -4.2% to 7.1%. , while pulses generally changed between -0.3% and 1.8% ,Milk remained the most stable, with changes mainly between 0.5% and 1.5%. Therefore, vegetables and fruits had greater price fluctuations, while milk and pulses were relatively stable or Lowest Inflation.

<img width="544" height="241" alt="image" src="https://github.com/user-attachments/assets/14834cdd-00e0-48c1-8a64-07c6a0d28e74" />

**Insight:**  From 2022 to 2023, Spices had the highest price increase, with growth of 11–12%, followed by cereals with 9–11%. Milk also increased by 6–7%. On the other hand, vegetables showed the biggest decrease of 13%, while oils and fats decreased by 5–8%. Meat and fish remained stable with 0% change. Overall, spices and cereals became more expensive, while vegetables and oils became cheaper.


### 4. Pre-COVID & Post-COVID Inflation Analysis

The project compares three major expenditure categories from 2013 to 2023:

<img width="591" height="323" alt="image" src="https://github.com/user-attachments/assets/ddee64e8-cff3-4da0-8ff3-e2f97577fa5a" />

**Key Findings:**

- Food & Beverages recorded approximately **7.77%** growth in 2020.
- Health recorded approximately 7.76% growth in 2021.
- Household Goods & Services recorded approximately 7.46% growth in 2022.
- All three categories experienced increases in their CPI index values over the analyzed period.

**Insight:** The COVID-period and subsequent years coincided with substantial increases in consumer price indices, although the magnitude varied by expenditure category.

### 5. Fuel & Light Vs Category Correlation Analysis

Correlation analysis was conducted to investigate the relationship between Fuel & Light price changes and other expenditure categories.

Fuel & Light has the strongest positive correlation with Non-alcoholic Beverages among the four comparisons.
<img width="470" height="240" alt="image" src="https://github.com/user-attachments/assets/a1803fbc-6e81-414e-b80e-8e8d52e4d492" />

Transport & Communication also exhibits a positive relationship with Fuel & Light.
<img width="557" height="281" alt="image" src="https://github.com/user-attachments/assets/967eb4d9-7990-4048-a25d-5d85b6dfdf28" />

Education has a relatively weak positive correlation.
<img width="581" height="296" alt="image" src="https://github.com/user-attachments/assets/644159b8-2fa1-4279-bc23-d1ea12b710bd" />

Food & Beverages has a weak negative correlation.
<img width="431" height="239" alt="image" src="https://github.com/user-attachments/assets/42ae8c84-25a7-467a-8515-92a2d25f26fb" />


**Key Insights:**

- Fuel & Light has the strongest positive correlation with Non-alcoholic Beverages among the four comparisons.
- Transport & Communication also exhibits a positive relationship with Fuel & Light.
- Education has a relatively weak positive correlation.
- Food & Beverages has a weak negative correlation.

**Insight:** Fuel price movements are more closely associated with transport and non-alcoholic beverage price movements than with education or overall food and beverage prices in this analysis.

## Overall Project Conclusions

The CPI analysis provides several important observations:

1. Food is the largest category by observation count in the transformed dataset.
2. Rural CPI remained above Urban CPI during the analyzed years.
3. The strongest annual increase in the General CPI Index occurred in 2022.
4. Vegetables demonstrated considerable monthly price volatility.
5. Spices and cereals recorded significant increases between 2022 and 2023.
6. The COVID-period and following years were associated with higher CPI index values across the selected categories.
7. Fuel & Light displayed stronger positive correlations with Transport & Communication and Non-alcoholic Beverages than with Education and Food & Beverages.

Overall, this project demonstrates how data analytics can help identify inflation patterns, understand commodity-level price movements, and explore relationships between different economic indicators.

## Methodology

The project follows a structured data analytics workflow:

**Step 1 – Data Collection:** Import the original CPI dataset.

**Step 2 – Data Cleaning:** Standardize data types and prepare the dataset for analysis.

**Step 3 – Data Transformation:** Unpivot the dataset to make category-level analysis easier.

**Step 4 – Data Classification:** Group individual CPI items into broader expenditure categories.

**Step 5 – Exploratory Analysis:** Use Pivot Tables to examine annual, monthly, category-wise, and sector-wise trends.

**Step 6 – Percentage Change Analysis:** Calculate changes in CPI indices over time.

**Step 7 – Correlation Analysis:** Evaluate relationships between Fuel & Light and selected CPI categories.

**Step 8 – Insight Generation:** Interpret the results and document the key findings.

## Project Highlights

- End-to-end Excel data analytics workflow.
- Data cleaning and transformation.
- 10,044 classified observations.
- Rural vs. Urban CPI comparison.
- Monthly and annual inflation analysis.
- Pre-COVID and post-COVID comparisons.
- Commodity-level trend analysis.
- Correlation analysis across four expenditure categories.
- Business-oriented interpretation of economic data.

## 👨‍💻 Author

**Drashti Patel**

*Aspiring Data Analyst | Excel | Economic Data Analysis*
Linkedin ID - www.linkedin.com/in/drashti-patel-038418303
Gmail ID - dvpatel050198@gmail.com
---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!

**Thank you for visiting my CPI Inflation Analysis Project.**
