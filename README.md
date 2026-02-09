# Data Analytics Portfolio

This portfolio showcases end-to-end data analytics projects spanning healthcare risk modeling, predictive analytics, business intelligence dashboards, and SQL-driven segmentation.

## Projects

### Healthcare Readmission Risk Analysis (SQL + Power BI)
**Tools:** SQL Server (T-SQL), Power BI, DAX 
- Analyzed 101,766 hospital encounters to identify drivers of 30-day readmission risk and developed an explainable rule-based patient stratification framework.
- Built SQL-based feature engineering pipeline (LOS grouping, emergency utilization flags)
- Identified high-risk diagnosis categories using volume-adjusted ranking queries
- Developed 3-tier risk model separating 16.9% (High Risk) vs 10.0% (Low Risk)
- Designed executive Power BI dashboard for operational intervention planning

View Project: https://github.com/kevin-rust/healthcare-readmission-risk-analysis

![Executive Overview](https://raw.githubusercontent.com/kevin-rust/healthcare-readmission-risk-analysis/main/images/executive_overview.png)

### Customer Churn Prediction (Python, scikit-learn)
**Tools:** Python, pandas, scikit-learn, matplotlib  
Built a logistic regression model to predict customer churn using a telecommunications dataset.
- Cleaned and preprocessed 7,000+ customer records
- Engineered features and encoded categorical variables
- Scaled numerical variables to improve model convergence
- Achieved ~79% accuracy with 52% recall on churners
- Identified key churn drivers including tenure, contract length, and fiber service usage

View project: https://github.com/kevin-rust/customer-churn-prediction

### Customer Segmentation Analysis (SQL + Python)
**Tools:** SQL Server, Python (pandas, matplotlib), Jupyter Notebook  
Analyzed retail transaction data to identify high-value customers and evaluate revenue concentration.  
- Cleaned and prepared raw transactional data using SQL  
- Aggregated customer-level metrics (Total Spend, Order Count, AOV)  
- Applied NTILE segmentation to classify customers by value  
- Identified that the top third of customers generate ~85% of total revenue  

View project: https://github.com/kevin-rust/customer-segmentation-analysis

### Business Performance Dashboard (Power BI)
**Tools:** Power BI, Power Query, DAX  
- An interactive dashboard analyzing retail sales performance by month, category, and region.
- Includes KPI tracking, trend analysis, and regional profitability insights.

View project: https://github.com/kevin-rust/business-performance-dashboard

Each project includes a README outlining the business problem, approach, and key insights.
