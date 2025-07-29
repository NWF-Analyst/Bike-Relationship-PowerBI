Power BI Portfolio: Bike Store Reporting Challenges

This project showcases a full suite of Power BI challenges based on the [Bike Store dataset from Kaggle](https://www.kaggle.com/datasets/ekrembayar/bike-stores). It simulates real-world reporting scenarios across sales, regions, customers, inventory, and forecasting.

> All dashboards were built without SQL, using Power Query, Data Modeling, Calendar Tables, and DAX Measures inside Power BI.

Core Concepts Used

✅ Data Modeling

 Star schema with fact and dimension tables
 Relationship setup using primary and foreign keys
 Consistent Calendar table for time intelligence

✅ DAX Measures

 Used `SUMX`, `CALCULATE`, `FILTER`, `DIVIDE`, `TOPN`, `VALUES`, and other advanced functions
 Created reusable metrics stored in a dedicated Measures Table

✅ Time Intelligence

 `Calendar` table with year, quarter, month, and day breakdowns
 Time-based analysis using `TOTALYTD`, `DATESINPERIOD`, `DATEADD`, etc.

✅ Power BI Techniques

 Drillthrough filters, tooltips, slicers
 Visual-level, page-level, and report-level filters
 Map and scatter charts
 Analytics pane: Anomalies

---

 💼 Challenge Breakdown

Each challenge was approached using this structure:

 Goal: What business question are we solving?
 Metric(s): What measures or KPIs did we calculate?
 Filters: What slicers or filtering logic is used?
 Tables: Which data tables are involved?
 Joins: What relationships were created?
 Method: Steps taken to clean, model, and visualize the data

---

 ✅ Completed Challenges
  No.            Challenge                                                                            Discription
  1  Dynamic Product Sales Dashboard        Matrix-based performance report for products across categories. Includes total revenue, quantity sold, and drillthrough by product.  
  2  Regional Performance Map               Map visuals for customer revenue by region. Scatter plot shows order count vs revenue per state. Includes drillthrough and tooltips. 
  3  Customer Lifetime Value Tracker        Tracks retention, frequency, first purchase, and top spender logic. Displays customer behavior and LTV over time.                    
  4  Procurement & Inventory Insight Board  Compares restock costs, flags fast/slow-moving inventory, and shows quantity sold by store. Matrix drillthrough included.            
  5  Monthly Sales Trend		                  Time series of monthly revenue with slicers for year/quarter. Anomaly detection using the Analytics pane.            

Outcome:
By the end of this project, I built a complete end-to-end BI reporting solution in Power BI from raw CSVs. All visuals were created using clean, well-modeled data and reusable DAX logic—no external SQL or data sources were needed.

Disclaimer:
This project was built entirely using Power BI to showcase data modeling, DAX measures, time intelligence, and visualization capabilities within the tool. While Power BI can efficiently handle datasets of this scale, SQL would be preferred for much larger datasets due to its superior performance in data storage and processing.
