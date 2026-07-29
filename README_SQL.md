# SaleOps: SQL Analysis of Car Sales Data
## Business Acumen & Revenue Growth Strategy

## Executive Summary- Analytical thinking & business interpretation
This project demonstrates the application of advanced SQL techniques—including Common Table Expressions (CTEs) and Window Functions—to transform raw car sales data into a strategic growth roadmap. Unlike standard reporting, this analysis focuses on revenue contribution, pricing power, and local market dynamics to provide a high-level view of business performance suitable for a BI or Data Analyst role.


### Dataset Overview 
- Dataset: Car sales dataset from Datacamp project's dataset.
- Focus: Analyzes revenue patterns and customer behavior across three regional warehouses (Central, North, and West).
- Data Integrity: Structured sales data with negligible payment fees and a focus on net revenue.

Note: The finding are for analytical and learning purposes only.

### Key Business Questions 
The analysis addresses the following key questions:
1. Revenue Contribution: What is the dominant product line per warehouse, and how much does it contribute to total regional revenue?
2. Product Prioritization: Which specific lines represent the best balance between demand and pricing power?
3. Local Dynamics: How do location-specific demands drive revenue disparities between warehouses?
4. Client Segmentation: How does the "bulk buying" nature of Wholesale clients compare to the "high unit price" Retail clients?
5. Operational Efficiency: Which warehouses are maximizing revenue per unit sold?

### Tools & Advanced SQL Skills
- Environment: Python, Jupyter Notebook, SQLite.
- Window Functions: Used SUM() OVER(PARTITION BY...) to calculate relative revenue contribution percentages.
- Ranking: Used DENSE_RANK() and ROW_NUMBER() to identify top and bottom performing product categories per region.
- CTEs: Used for multi-stage data transformation to isolate net revenue metrics.
- Business Interpretation: Converting SQL outputs into actionable advice (e.g., inventory reallocation strategies).

Note:This project focuses on SQL-based Analysis(Basic to Advance); no visulizations are included. 


### Final Strategic Insights
The analysis reveals distinct regional profiles that require different business strategies: 
- Growth Leader (Central): Demonstrates the strongest operational performance with the highest revenue efficiency per unit.
- Optimization Target (North): Shows competitive volume but requires product mix optimization to improve contribution margins.
- Turnaround Opportunity (West): Underperforms in volume; however, high retail unit pricing suggests a niche market that could benefit from inventory reallocation of high-performing lines like "Frame & Body". 
- Core Driver: "Suspension & Traction" is the dominant revenue driver across all regions, while "Frame & Body" offers the best balance for profit growth due to superior pricing power.
These insights support data-driven operational and startegic decisions.

## Author
[Pyae Khant Kyaw](https://www.linkedin.com/in/pyae-khant-kyaw-591726390/)
