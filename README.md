# Excel-Bike-Sales-Visualization-
# 🚴 Bike Sales Analysis & Visualization

This repository contains an in-depth analysis of global bike sales data, utilizing Microsoft Excel to create an interactive dashboard and various data visualizations. The project aims to uncover key performance indicators (KPIs), identify major revenue drivers (product, geography, and customer segment), and visualize sales trends over time.

## 📊 Key Findings & Visualizations

The analysis is based on aggregated data, revealing significant trends across time, geography, product, and customer age.

### 1. Annual Revenue and Profit Growth

* **Finding:** The company has experienced **significant, consistent growth** in both annual **Revenue** and **Profit** from 2017 to 2021.
* **Recommendation:** A **Line Chart** to visualize the time-series trend, demonstrating the sharp increase from 2017 (Revenue: ~\$10.3M, Profit: ~\$4.1M) to 2021 (Revenue: ~\$29.7M, Profit: ~\$13.0M).

| Year | Annual Revenue | Annual Profit |
| :---: | :---: | :---: |
| 2017 | $10,289,670 | $4,065,680 |
| 2021 | $29,747,226 | $12,986,202 |
| **Total** | **$95,176,318** | **$42,126,410** |

***<img width="658" height="290" alt="image" src="https://github.com/user-attachments/assets/709dbf56-b986-42c6-9f54-6ab0387548e5" />


### 2. Product and Geographical Performance

* **Finding: Product Dominance:** **Bikes** is the dominant product category, accounting for a majority of the total revenue (~$69.2M). **Accessories** (~$16.7M$) and **Clothing** (~$9.3M$) are significantly smaller contributors.
* **Finding: Top Markets:** The **United States** (~$30.8M$) and **Australia** (~$25.4M$) are the two largest markets by revenue, collectively generating over half of the total sales.
* **Recommendation:** A **Stacked Bar Chart** (or a **Clustered Column Chart**) to visualize **Revenue by Country** and break it down by **Product Category** (Bikes, Accessories, Clothing). This highlights which countries are driving the overall Bike sales.

| Country | Bikes Revenue | Total Revenue |
| :--- | :---: | :---: |
| United States | $21,551,497 | $30,814,774 |
| Australia | $20,231,486 | $25,427,586 |
| **Grand Total** | **$69,208,196** | **$95,176,318** |

***<img width="815" height="338" alt="image" src="https://github.com/user-attachments/assets/4ce51dea-f0a8-4d0a-a03d-88843960e104" />


### 3. Revenue by Customer Age Group

* **Finding:** The **Adults (35-64)** segment is the largest revenue source (~$47.3M$), followed closely by **Young Adults (25-34)** (~$34.3M$).
* **Finding: Opportunity:** The **Seniors (64+)** segment generates the lowest revenue (~$0.34M$), indicating a potential area for targeted marketing or product development.
* **Recommendation:** A **Pie Chart** or **Doughnut Chart** to show the revenue distribution by **Age Group**, immediately highlighting the dominance of the 'Adults (35-64)' and 'Young Adults (25-34)' groups, and the small share of 'Seniors (64+)'.

| Age Group | Sum of Revenue | Percentage of Total |
| :--- | :---: | :---: |
| Adults (35-64) | $47,323,876 | ~ 50% |
| Young Adults (25-34) | $34,310,905 | ~ 36% |
| Youth (<25) | $13,201,837 | ~ 14% |
| Seniors (64+) | $339,700 | ~ 0.4% |

***
<img width="566" height="281" alt="image" src="https://github.com/user-attachments/assets/7b22257a-8493-4b88-8b75-78a0648d6956" />

## ⚙️ Technologies Used

* **Microsoft Excel:** Data cleaning, aggregation (Pivot Tables), formula-based calculations, and dynamic dashboard creation.
* **CSV Files:** The raw and aggregated data are provided in CSV format (originally from an Excel Workbook).

***

## 📄 Data Source

The analysis is based on four datasets:
1.  `... - Sales Data.csv`: The main transactional dataset.
2.  `... - Revenue and Profit by Year.csv`: Annual performance summary.
3.  `... - Product Revenue by Country.csv`: Revenue breakdown by product category and geography.
4.  `... - Revenue by Age Group.csv`: Revenue segmented by customer age group.
