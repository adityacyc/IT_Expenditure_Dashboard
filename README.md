# IT_Expenditure_Dashboard
Project Overview

This project analyzes IT expenditure data using Power BI to provide insights into organizational spending patterns, budget performance, forecasting accuracy, and cost distribution across different business units, regions, and IT categories.

The dashboard enables stakeholders to monitor actual expenses, compare them against planned budgets and forecasts, identify cost variances, and support data-driven financial decision-making.

Objectives
Analyze total IT expenditure across the organization.
Compare Actual, Forecast, and Planned costs.
Identify budget variances and overspending areas.
Track expenditure trends over time.
Evaluate spending distribution by region, business unit, and IT category.
Support financial planning and resource allocation.
Dataset Information

The dataset contains IT expenditure-related information, including:

Date
Region
Business Unit
IT Area/Category
Actual Cost
Forecast Cost
Planned Cost
Data Preparation

The following preprocessing steps were performed:

Imported Excel data into Power BI.
Standardized column names.
Handled missing and null values.
Formatted date fields.
Created relationships between tables (if applicable).
Developed calculated columns and measures using DAX.
Key Metrics
Total IT Spend
Actual Spend
Forecast Spend
Planned Spend
Variance Analysis
Actual vs Plan Variance
Actual vs Forecast Variance
Variance Percentage
Category Analysis
Spend by IT Area
Spend by Business Unit
Spend by Region
Trend Analysis
Monthly IT Expenditure Trend
Actual vs Forecast Trend
Actual vs Plan Trend
DAX Measures Used

Examples of DAX measures used in the project:

Total Actual Spend =
SUM('IT Expenditure'[Actual])

Total Forecast Spend =
SUM('IT Expenditure'[Forecast])

Total Planned Spend =
SUM('IT Expenditure'[Plan])

Variance vs Plan =
[Total Actual Spend] - [Total Planned Spend]

Variance % =
DIVIDE(
    [Variance vs Plan],
    [Total Planned Spend],
    0
)
Dashboard Features
Executive Summary Page
IT Cost Breakdown Analysis
Variance Analysis
Regional Spend Analysis
Business Unit Performance
Time-Series Trend Analysis
Interactive Filters and Slicers
Tools & Technologies
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Microsoft Excel
Insights Generated
Identified high-cost IT categories.
Highlighted regions exceeding budget targets.
Compared forecasted and actual expenditures.
Tracked spending trends for financial planning.
Detected areas requiring cost optimization.
Project Structure
IT-Expenditure-Analysis/
│
├── Dataset/
│   └── IT Expenditure Dataset.xlsx
│
├── PowerBI/
│   └── IT Expenditure Analysis.pbix
│
├── Screenshots/
│   └── Dashboard Images
│
├── README.md
│
└── Documentation/
    └── Project Report.pdf
Dashboard Screenshot

Add screenshots of your Power BI dashboard here after uploading them to GitHub.

Conclusion

This dashboard provides a comprehensive view of IT expenditure performance by comparing actual spending against forecasts and plans. It helps management monitor budgets, identify spending patterns, and make informed financial decisions.

Author

Aditya Singh

B.Tech (Mechanical Engineering)
MBA (Finance & Marketing)
Aspiring Data Analyst
Power BI | SQL | Python | Excel
