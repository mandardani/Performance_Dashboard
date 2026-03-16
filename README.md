# Performance_Dashboard
Plant Operations &amp; Sales Performance Dashboard
<img width="1295" height="833" alt="Screenshot 2026-03-16 092308" src="https://github.com/user-attachments/assets/aa5ee065-0d8d-4d14-9a41-f72b9fa39328" />

1. Executive Summary</br>
This Power BI presentation is designed to monitor plant performance, financial health, and operational efficiency. It translates raw manufacturing and accounting data into actionable insights for stakeholders to track budget variances and production output.</br>
2. Data Architecture</br>
The dashboard is built upon a relational model consisting of three primary datasets:</br>
•	Plant_FACT: The central transactional table containing volume, budget, and actual performance metrics.</br>
•	Accounts: A dimension table defining the financial structure, including Gross Margin, Net Sales, and Cost of Goods Sold (COGS).</br>
•	Plant_Hierarchy: A structural table that organizes data by Product, Plant, and Geographic location.</br>
3. Key Metrics & KPIs</br>
The dashboard tracks several critical measures to assess organizational health:</br>
•	Total Volume: Aggregated production or sales units across all plant locations.</br>
•	Budget vs. Actual: A comparative analysis of financial targets against realized performance.</br>
•	Gross Margin %: Efficiency metric calculated from Net Sales and COGS.</br>
•	Plant Efficiency: Performance tracking at the individual facility level.</br>
4. Visual Interface</br>
The reporting layer utilizes the CY26SU02 base theme for a professional, high-contrast aesthetic. Key visual elements include:</br>
•	Regional Performance Map: Visualizes plant output across different territories.</br>
•	Trend Analysis Lines: Displays volume and revenue fluctuations over the academic/fiscal semesters.</br>
•	Variance Slicers: Allows users to filter data by specific accounts or plant hierarchies to isolate performance gaps.</br>
5. Technical Specifications</br>
•	Platform: Power BI Desktop.</br>
•	Data Model Type: Star Schema (Fact and Dimension relationship).</br>
•	Internal Theme: Accessible Default with custom JSON modifications.</br>
