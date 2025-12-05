# Vendor-Performance-analysis-
Vendor Performance Analysis Dashboard - A complete analytics pipeline (SQL → Python → Power BI) that transforms raw procurement data into actionable business insights. Features vendor segmentation, profitability analysis, inventory optimization, and interactive dashboards to drive strategic decision-making.

📊 Project Overview
An end-to-end analytics project analyzing vendor performance to optimize procurement strategies, reduce costs, and improve profitability in retail/wholesale operations. This production-ready case study demonstrates full-stack analytics capabilities from data extraction to interactive visualization.

🚀 Tech Stack
SQL: Data extraction, transformation, and aggregation

Python: Exploratory Data Analysis, statistical testing, data cleaning

Power BI: Interactive dashboard creation and visualization

Database Management: Data storage and retrieval optimization

📈 Key Metrics Tracked
Total Sales: $461.41M

Gross Profit: $307.34M

Profit Margin: 38.7%

Unsold Inventory: $2.71M

Vendor Concentration: Top 10 vendors contribute 65.69% of purchases

🔄 Project Pipeline
Phase 1: Data Engineering & SQL
Database Exploration: Understand table structures and relationships

Data Merging: Combine multiple procurement and sales tables

Data Cleaning: Handle missing values, outliers, and inconsistencies

Aggregation: Create vendor-level performance metrics

Database Storage: Save processed tables for analysis

Phase 2: Analytics & Python
Exploratory Data Analysis: Statistical summaries and correlation analysis

Data Cleaning: Filtering negative profits and zero-sales items

Research Questions:

Identify brands for promotional adjustments

Analyze bulk purchasing impact (72% cost savings)

Assess inventory turnover and holding costs

Compare high vs. low-performing vendor profitability

Statistical Validation: Hypothesis testing for profit margin differences

Phase 3: Visualization & Reporting
Power BI Dashboard: Interactive vendor performance dashboard

Report Writing: Comprehensive business insights and recommendations

Actionable Insights: Strategic recommendations for procurement optimization

📁 Repository Structure
text
vendor-performance-analysis/
├── sql/
│   ├── database_exploration.sql
│   ├── data_cleaning.sql
│   ├── data_aggregation.sql
│   └── table_creation.sql
├── python/
│   ├── data_loading.ipynb
│   ├── exploratory_analysis.ipynb
│   ├── research_questions.ipynb
│   └── statistical_testing.ipynb
├── powerbi/
│   ├── vendor_dashboard.pbix
│   ├── data_model.bim
│   └── visuals/
├── data/
│   ├── raw/
│   ├── processed/
│   └── aggregated/
├── reports/
│   ├── business_insights.pdf
│   └── technical_documentation.md
├── README.md
└── requirements.txt
🎯 Business Impact
This analysis enables:

Cost Reduction: 72% unit cost savings through bulk purchasing

Risk Mitigation: Vendor diversification strategy

Profit Optimization: 41.55% vs 31.17% margin comparison insights

Inventory Efficiency: $2.71M unsold inventory identification

Strategic Decision Making: Data-driven vendor management

🛠️ Installation & Usage
Prerequisites
bash
# Python dependencies
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter

# Database
# SQL Server / PostgreSQL with procurement database

# Visualization
# Power BI Desktop
Setup Instructions
Database Setup: Run SQL scripts in /sql/ to create and populate tables

Python Analysis: Open Jupyter notebooks in /python/ for data analysis

Dashboard: Load Power BI file in /powerbi/ to explore interactive visuals

📊 Dashboard Features
Vendor Performance Overview: Key metrics at a glance

Profitability Analysis: Margin comparison across vendor segments

Inventory Health: Stock turnover and unsold inventory tracking

Purchase Optimization: Bulk purchasing impact visualization

Vendor Risk Assessment: Concentration and dependency analysis

🎯 Key Findings & Recommendations
Critical Insights
Vendor Concentration Risk: Top 10 vendors represent 65.69% of purchases

Bulk Purchase Advantage: 72% lower unit cost for large orders

Inventory Inefficiency: $2.71M tied in unsold stock

Margin Disparity: Low-performing vendors have higher margins (41.55%) but lower sales

Statistical Validation: Significant difference in vendor profitability models

Strategic Recommendations
Immediate: Diversify vendor base, launch clearance sales

Short-term: Optimize pricing for 198 identified brands

Long-term: Implement bulk purchasing program, enhance vendor relationship management

📈 Success Metrics
Reduce unsold inventory by 20%

Improve overall profit margins by 10-15%

Decrease top vendor dependency to below 50%

Increase sales volume for targeted brands by 25%
