# Customer Segmentation Dashboard – Power BI

This project focuses on segmenting customers based on purchasing behaviour and demographic attributes using clustering techniques. The final segmented dataset is visualized in Power BI to help identify customer groups and understand marketing opportunities.

---

## Objective
To analyze customer patterns and divide customers into meaningful clusters so that businesses can target groups more effectively and optimize marketing strategies.

---

## Dataset
The project uses the provided dataset `clustered_customers.csv`, which includes the following major attributes:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score
- Cluster Label (generated through clustering)

---

## Methodology

### 1. Data Preparation
- Renamed columns and removed duplicates
- Standardized customer attributes
- Handled missing values (if any)

### 2. Clustering
- Applied clustering technique (K-Means / similar ML method) to create customer segments
- Final dataset contains a **Cluster** column representing customer group assignment

### 3. Power BI Visualization
The clustered dataset was imported into Power BI to build an interactive dashboard including:

| Visualization | Insight Provided |
|--------------|------------------|
| Cluster distribution chart | Total number of customers per segment |
| Age vs Spending Score | Customer lifestyle and buying pattern |
| Income vs Spending Score | High-value and low-value customer analysis |
| Gender-wise segmentation | Demographic insights |
| Slicers | Cluster-based dynamic filtering |

---

## Key Insights
- Different clusters reflect unique spending patterns and income groups
- Helps identify:
  - Premium high-spending customers
  - Young shoppers with moderate income but high spend behavior
  - Low-spend customers for retention campaigns
  - Customers highly influenced by discounts

---

## Tools and Technologies
| Layer | Tools Used |
|-------|------------|
| Data Analysis | Python / Excel |
| Clustering | K-Means (or similar algorithm) |
| Visualization | Power BI |
| Dataset Format | CSV |

---

## How to Use
1. Open Power BI Desktop
2. Import `clustered_customers.csv`
3. Refresh data if needed
4. Explore dashboard using filters to compare clusters and attributes

---

## Conclusion
This Customer Segmentation Dashboard helps businesses understand customer groups, improve marketing strategies, and focus on high-value segments. It supports data-driven decisions for personalized offers, customer experience improvement, and revenue growth.

---

## Author
Developer: Brijesh Maurya  
Final Year IT Engineering Student  
Interest Areas: Data Science, Machine Learning, Business Intelligence

