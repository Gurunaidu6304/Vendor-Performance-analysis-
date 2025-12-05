# Vendor-Performance-analysis-
VENDOR PERFORMANCE ANALYSIS
📊 Project Overview
Vendor Performance Analysis Dashboard is an end-to-end analytics project that transforms raw procurement data into actionable business insights. This production-ready solution demonstrates full-stack analytics capabilities using SQL for data processing, Python for advanced analysis, and Power BI for interactive visualization.

 View Dashboard

 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f2ba6fe3-b25f-44bf-a62b-6175c39afea8" />




🎯 Business Problem
Retail and wholesale companies face significant challenges in optimizing vendor performance, managing inventory costs, and maintaining profitability. This project addresses:

Vendor Concentration Risk: Over-reliance on top suppliers

Inventory Inefficiency: High unsold inventory costs

Profit Margin Disparities: Inconsistent profitability across vendors

Bulk Purchase Optimization: Missed cost-saving opportunities

📈 Key Performance Metrics
Metric	Value	Insight
Total Sales	$461.41M	Overall business scale
Gross Profit	$307.34M	Revenue after cost of goods
Profit Margin	38.7%	Overall profitability percentage
Unsold Inventory	$2.71M	Capital tied in slow-moving stock
Top Vendor Contribution	65.69%	Concentration risk indicator
🏗️ Architecture & Pipeline





<img width="3803" height="917" alt="deepseek_mermaid_20251205_7b3fb5" src="https://github.com/user-attachments/assets/2bba9709-512b-4cbe-a2f5-f3a26bd9ea9e" />








🔧 Tech Stack
Data Processing
SQL: Data extraction, transformation, and aggregation

PostgreSQL: Database management and querying

Analytics & Modeling
Python 3.8+: Core analysis engine

Pandas: Data manipulation and analysis

NumPy: Numerical computations

SciPy/Statsmodels: Statistical testing

Matplotlib/Seaborn: Data visualization

Visualization & Reporting
Power BI: Interactive dashboards

Jupyter Notebooks: Exploratory analysis

Markdown: Documentation and reporting

📁 Project Structure
text
Vendor-Performance-analysis/
├── 📂 sql/
│   ├── database_setup.sql          # Database creation and schema
│   ├── data_extraction.sql         # Raw data extraction queries
│   ├── data_transformation.sql     # Cleaning and transformation
│   └── aggregations.sql            # Vendor-level aggregations
├── 📂 notebooks/
│   ├── 01_data_loading.ipynb       # Data ingestion and validation
│   ├── 02_exploratory_analysis.ipynb # EDA and visualization
│   ├── 03_statistical_analysis.ipynb # Hypothesis testing
│   └── 04_research_questions.ipynb  # Business insights
├── 📂 powerbi/
│   ├── Vendor_Dashboard.pbix       # Interactive Power BI file
│   ├── data_model/                 # Data model configuration
│   └── assets/                     # Images and resources
├── 📂 data/
│   ├── raw/                        # Original data files
│   ├── processed/                  # Cleaned data
│   └── outputs/                    # Analysis results
├── 📂 reports/
│   ├── business_report.pdf         # Executive summary
│   ├── technical_documentation.md  # Implementation details
│   └── presentations/              # Presentation decks
├── 📂 src/
│   ├── data_processing.py          # Python data processing modules
│   ├── analysis_functions.py       # Analytical functions
│   └── visualization.py            # Plotting utilities
├── README.md                       # This file
├── requirements.txt               # Python dependencies
└── LICENSE                        # MIT License
📊 Analysis & Insights
1. Vendor Performance Segmentation

Key Finding: Identified 198 brands with high profit margins but low sales volume, representing untapped growth opportunities.

2. Bulk Purchase Cost Analysis
Key Finding: Bulk purchasing delivers 72% lower unit costs ($10.78/unit vs. higher unit costs), highlighting significant savings opportunities.

3. Inventory Turnover Analysis
Key Finding: Stock turnover ranges from 0 to 274.5, with $2.71M tied in unsold inventory, indicating optimization potential.

4. Profit Margin Comparison
Statistical Validation:

High-performing vendors: 31.17% mean margin

Low-performing vendors: 41.55% mean margin

p-value < 0.05: Statistically significant difference

📈 Dashboard Features
Executive Overview

Key Sections:
Performance Metrics: Real-time KPI tracking

Vendor Ranking: Top/Bottom performers visualization

Profitability Analysis: Margin trends and comparisons

Inventory Health: Turnover rates and stock levels

Purchase Optimization: Bulk buying impact analysis

Risk Assessment: Vendor concentration metrics

🚀 Getting Started
Prerequisites
bash
# Python 3.8 or higher
python --version

# PostgreSQL or compatible database
# Power BI Desktop (for dashboard)
Installation
Clone the repository

bash
git clone https://github.com/Gurunaidu6304/Vendor-Performance-analysis-.git
cd Vendor-Performance-analysis-
Set up Python environment

bash
# Create virtual environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
Database Setup

sql
-- Run the SQL scripts in order
\i sql/database_setup.sql
\i sql/data_extraction.sql
\i sql/data_transformation.sql
\i sql/aggregations.sql
Run Analysis

bash
# Launch Jupyter Notebook
jupyter notebook

# Open and run notebooks in order:
# 01_data_loading.ipynb
# 02_exploratory_analysis.ipynb
# 03_statistical_analysis.ipynb
# 04_research_questions.ipynb
Explore Dashboard

Open powerbi/Vendor_Dashboard.pbix in Power BI Desktop

Connect to your processed data source

Refresh and explore interactive visuals

📋 Research Questions & Findings
Q1: Which brands need promotional adjustments?
Answer: 198 brands identified with high margins but low sales. Recommended targeted marketing campaigns.

Q2: What's the bulk purchase impact?
Answer: 72% unit cost reduction, suggesting strategic bulk purchasing programs.

Q3: Which vendors have low inventory turnover?
Answer: Identified vendors with $2.71M in unsold inventory. Recommended clearance strategies.

Q4: Profit margin differences between vendor groups?
Answer: Statistically significant difference (41.55% vs 31.17%). High-margin vendors need sales volume improvement.

🎯 Business Recommendations
Immediate Actions (1-3 months)
Launch clearance sales for $2.71M unsold inventory

Implement targeted promotions for 198 high-margin, low-sales brands

Negotiate bulk discounts with top vendors

Strategic Initiatives (3-12 months)
Diversify vendor base to reduce 65.69% concentration risk

Implement inventory optimization system

Develop vendor performance scorecard

Create automated reporting dashboard

📊 Expected Business Impact
Metric	Current	Target	Improvement
Unsold Inventory	$2.71M	$2.17M	-20%
Profit Margin	38.7%	42.6%	+10%
Top Vendor Dependency	65.69%	<50%	-24%
Bulk Purchase Adoption	Low	High	+50%
🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add some AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Dataset adapted from real-world procurement scenarios

Inspired by retail/wholesale industry challenges

Built for educational and portfolio purposes
