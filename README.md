# Cluster Profitable Trend Analysis (Interactive Dashboard using Power BI)

### Project Objective

Build an interactive dashboard that tracks cluster performance across cities (2022-2024), so the business can understand revenue, churn, profitability and cluster maturity, and focus on the cities and clusters that drive growth.

### Note :
Due to data privacy and company confidentiality policies, raw datasets, customer records, and the original workbook are proprietary and cannot be shared publicly.

### Dataset Used
Cluster-level data covering Cluster ID, City, Month, Year, Base CM, Cluster Revenue, Churn, ARPU, Penetration, EBITDA, GAD FTM, AON bucket, Operating Margin Status and Cluster Ageing.

Questions (KPIs)
- What is the total Base CM and the total number of clusters?
- Which city contributes the most cluster revenue?
- Which city has the highest average churn?
- How many churn cases come from each city?
- How does GAD FTM vary by AON (age on network) bucket?
- How are clusters distributed across ARPU, Revenue, Penetration and EBITDA buckets?
- How do results change by month, year, operating margin status (Negative/Positive) and cluster ageing (> 12 months / < 12 months)?

### Process
- Checked the data for missing values and anomalies and cleaned them.
- Made sure data types, formats and values were consistent.
- Created measures and buckets (ARPU, Revenue, Penetration, EBITDA, AON, Churn).
- Built the visuals: KPI cards, bar chart, donut chart, funnel chart, AON bar chart and bucket tables.
- Combined everything on one dashboard and added slicers (Month, Year, Operating Margin Status, Cluster Ageing) to make it dynamic.

Dashboard
![Cluster Profitable Dashboard](https://github.com/Abhijeetpatil-1998/Cluster-Profitable-Trend-Analysis-Interactive-Dashboard-using-Power-BI-/blob/main/Cluster%20Profitable%20Dashboard.jpeg)

### Project Insights
- Pune and MMR are the top revenue cities, and together they contribute well over half of the revenue shown for the top cities.
- Jaipur has the highest average churn (21.83%) despite lower revenue, followed by Pune (19.75%), so retention needs attention there.
- MMR and Bengaluru have the highest number of churned clusters (2,993 and 2,844), even though their average churn rates are lower, because of their larger cluster base.
- Mature clusters (M24+ and M13-M24) generate most of the GAD FTM (about 256K of ~314K), while newer clusters (M0-M6) contribute very little.
- Most clusters sit in the 800-900 ARPU bucket (6,625 of 12,771), and 6,642 clusters have penetration above 10%.
- 6,969 clusters fall in the lowest EBITDA bucket (< 25,000), showing a large share of low-profit clusters.
- 3,555 clusters earn more than 500,000 in revenue, the largest revenue bucket.

### Final Conclusion

To grow the business, focus on retention in high-churn cities such as Jaipur and Pune, while protecting revenue in Pune and MMR. Nurture newer clusters so they mature past 12 months, since older clusters drive most of the GAD FTM. Improve EBITDA in the large group of low-profit clusters through cost control and ARPU uplift, and use the Month, Year, Margin Status and Ageing slicers to track progress regularly.

### Tools Used
- Power BI Desktop (Data model, DAX, Visuals, Slicers)
- Microsoft Excel (Data cleaning)

