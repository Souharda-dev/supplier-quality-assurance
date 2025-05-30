Supplier Performance Analytics & Forecasting for FMCG Chocolate Brand
A Power BI & Time Series Forecasting Solution

📌 Project Overview
This project helps a Fortune 500 FMCG chocolate brand optimize its supplier base by:
✅ Evaluating supplier performance using key metrics (quality, cost, delivery)
✅ Forecasting future reliability using Prophet time-series models
✅ Visualizing insights in an interactive Power BI dashboard

📊 Key Deliverables
1. Supplier Scorecard
Metrics: Overall score, defect rate, on-time delivery %, lead time

Visual: Multi-row card with KPIs

2. Performance Trends
Time-series analysis of quality & delivery metrics

Forecasted trends (12-24 months ahead)

3. Supplier Risk Matrix
Scatter plot comparing current performance vs. forecasted trend

Risk categorization (Strategic, Stable, High-Risk)

4. Cost vs. Quality Heatmap
Matrix visual showing cost efficiency per supplier & material

5. Geographic Risk Map
World map highlighting supplier locations with risk scores

6. Forecast Accuracy Monitoring
Waterfall chart tracking forecast vs. actual performance

7. Interactive Dashboard
Slicers for time period, material type, and risk level

⚙️ Technical Implementation
📂 Data Sources
ERP/Procurement Systems (SAP, Oracle)

Supplier Master Data (lead times, defect rates, costs)

External Data (country risk indices, commodity prices)

🔧 Tools Used
Tool	Purpose
Power BI	Dashboarding & visualization
Python (Prophet)	Time-series forecasting
DAX	Calculated metrics & KPIs
Power Query	Data cleaning & transformation
📈 Forecasting Model
Algorithm: Facebook’s Prophet

Metrics Forecasted:

On-time delivery %

Defect rates

Lead time variability

🚀 How to Use This Dashboard
Connect Data Sources

Import supplier performance data (Excel, SQL, or ERP)

Ensure date fields are formatted correctly

Set Up Forecasts

Run the Python script (included) to generate Prophet forecasts

Load forecast data into Power BI

Customize Metrics

Adjust weights in the supplier scoring formula

Modify risk thresholds as per business needs

Interact with the Dashboard

Filter by time period, material, or supplier risk

Drill down into specific suppliers for detailed analysis

📌 Business Impact
🔹 Identify top-performing suppliers for long-term contracts
🔹 Detect at-risk suppliers before disruptions occur
🔹 Optimize procurement costs by balancing quality & price
🔹 Improve supply chain resilience with data-driven decisions

📂 Folder Structure
📦 supplier-performance-analysis/  
├── 📄 README.md                 # This file  
├── 📊 PowerBI_Dashboard.pbix    # Interactive dashboard  
├── 📜 Forecast_Model.py         # Python Prophet forecasting  
├── 📂 Data/                     # Sample datasets  
│   ├── suppliers.csv           # Supplier performance data  
│   ├── forecast_results.csv    # Forecast outputs  
│   └── country_risk.csv        # Geo-political risk data  
└── 📂 Documentation/            # Additional guides  
    ├── DAX_CheatSheet.md       # Key measures explained  
    └── User_Guide.pdf          # Dashboard instructions  
📅 Next Steps
Import your actual supplier data

Adjust forecasting parameters for better accuracy

Schedule automatic refreshes in Power BI Service

Train procurement team on using the dashboard

