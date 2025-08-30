# AtliQ Mart Supplychain Analysis
Power BI Project
## 📋Project Overview
Developed a Power BI supply chain dashboard to track OT%, IF%, OTIF%, fill rates, and delay days, enabling city, customer, and product-level insights to improve delivery performance and customer satisfaction.
## ❓Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities: Surat, Ahmedabad, and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers have not extended their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer. 
## ✅Metrics Tracked
-  On-Time Delivery (OT) %: Measures the percentage of customer orders delivered on time.
-  In-Full Delivery (IF) %: Measures the percentage of customer orders delivered in full.
-  On-Time In Full (OTIF) %: Measures the percentage of customer orders that are both on-time and in-full.
## 🖥️Live Dashboard
Link for the AtliQ mart Supplychain Dashboard -  [Live Dashboard]( https://app.powerbi.com/view?r=eyJrIjoiZjNkOWY3NjItZGNkYi00OThmLTgyOTYtNGZkODM2YjU5ZWUzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
## 🗂️Datasets
Before starting the analysis, it’s important to understand the structure of the data. The project uses two main types of tables:

 -  **Dimension Table:** Contains static reference data such as customer information, product details.
-  **Fact Table:** Contains Transactional data.
### **Tables**
-  dim_customer
-  dim_product
-  dim_date
-  dim_targets_orders
-  fact_order_lines
-  fact_orders_aggregate
 ##  🔗Data modeling
 Data modeling in Power BI is the process of connecting and organizing tables with relationships so data can be analyzed effectively.
 In Power BI projects, data modeling defines how different tables relate to each other, which helps create accurate reports and visualizations.
 ### A good data Modeling
-  Separates facts (numbers or transactions) from dimensions (descriptive details)
-  Uses clear relationships so tables link correctly
-  Avoids repetition to save space and reduce errors
-  Designed to make analysis fast and simple

   In this project, we used a Star  schema for data modeling, which keeps the data organized, easy to manage, and ready for creating clear and useful reports.
   
   ![Datamodeling](https://github.com/Shahna-k25/AtliQ-Mart-Supplychain-Analysis/blob/main/Supply%20datamodeling.png)
 ## 🌐Technologies Used
 -  Power BI → For building dashboards, KPIs, and interactive visuals
 -  Excel → As source files for fact and dimension tables
 -  DAX (Data Analysis Expressions) → To create calculated columns, measures, and service-level metrics
 -  Data Visualization → Bar charts, line charts, heatmaps, and KPI cards to track performance
## 📈Power BI Techniques Learned
- Data Modeling → Linking fact & dimension tables with relationships
- DAX Measures & Calculated Columns → Service level %, OTIF %, Avg Delay Days, Fill Rate %
- KPI Cards → Showing On-Time %, In-Full %, and OTIF % against targets
- Filters & Slicers → Splitting insights by city, customer, and product
- Page Navigation → Creating multi-page dashboards (Overview,  Trend& Product Insights)
- Conditional Formatting → Highlighting delays and underperforming customers/products
## 🌟Key Highlights
- Developed a comprehensive supply chain performance dashboard
- Tracked On-Time, In-Full, and OTIF % against targets
- Created city-wise, customer-wise, and product-wise breakdowns for deeper insights
- Added insights on average delivery delay days and fill rate %
- Designed multi-page dashboard (Overview, Customer, Product Insights
- Delivered actionable insights to improve service levels and supply efficiency
## 📝Key Learnings
-  Understood how to design a star schema data model (facts vs. dimensions)
-  Learned to create calculated columns & DAX measures (OT%, IF%, OTIF%, Fill Rate, Delay Days)
-  Applied Power BI techniques like filters,  conditional formatting,page navigation  and slicers
-  Gained skills in data cleaning, transformation, and relationships using Power Query
-  Improved ability to design multi-page dashboards with business-focused visuals
-  Learned how to convert raw supply chain data into actionable insights for decision-making
## 🎯Conclusion
This project helps the supply chain team measure service levels in a clear and consistent way using OT%, IF%, and OTIF%. 
By checking these every day against the target for each customer, the team can quickly see where deliveries are on track and where problems exist. 
This makes it easier to improve delivery performance, keep customers happy, and build stronger trust through reliable service.
