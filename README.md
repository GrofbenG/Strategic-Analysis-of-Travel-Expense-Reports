# Travel Expense Data Analysis

##  Overview
This project analyzes travel expense data to identify inefficiencies, data quality issues, and their impact on business KPIs.

##  Business Problem
Travel expense reporting systems can produce misleading KPIs if data quality issues are present. The goal was to identify anomalies and improve reporting reliability.

## 🛠 Tools Used
- Python (pandas)
- SQL
- Tableau

##  Dataset
- ~10,000 records
- Expense reports and submission timestamps

##  Key Findings
- Identified extreme outliers (700+ day delays) significantly distorting KPIs
- Detected timestamp inconsistencies (negative delays)
- Found gaps in validation and reporting logic

##  Business Impact
- Distorted performance metrics
- Reduced trust in reporting
- Potential compliance risks

##  Recommendations
- Implement validation rules for date logic
- Flag anomalies automatically
- Use median and percentile metrics instead of averages

##  Project Structure
- Notebook: full analysis
- Data: sample dataset
- Images: visualizations

##  Next Steps
- Build interactive dashboard
- Automate validation checks
