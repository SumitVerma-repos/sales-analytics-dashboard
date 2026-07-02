# sales-analytics-dashboard

## Objective
The executive team requested a dynamic dashboard to analyze sales activities, track revenue trends, and identify top-performing stores, brands, and sales representatives over the 2016-2018 period. 

## Technical Toolkit
* **Database Management:** MySQL for querying and joining 9 related tables to construct a comprehensive foundational dataset.
* **Data Analysis & Visualization:** Microsoft Excel (Pivot tables, Slicers) and Tableau for building interactive, executive-level dashboards.

## Process
1.  **Data Extraction:** Wrote an optimized SQL script to extract order details, customer demographics, and product revenue. Used `CONCAT`, `SUM`, and multiple `JOIN` clauses to unify the relational data.
2.  **Excel Dashboarding:** Connected the SQL database to Excel. Built a dynamic dashboard utilizing pivot charts and slicers to allow management to filter metrics seamlessly by year, state, and store.
3.  **Tableau Visualization:** Imported the dataset into Tableau to create an advanced visual dashboard featuring map charts, tree maps (for product categories), and custom calculated fields to track profitability at a glance.

## Key Insights
* **Regional Performance:** New York consistently generated the highest total revenue across the analyzed period, while Texas generated the lowest. 
* **Year-Over-Year Variability:** Top performers shifted notably between years. For instance, in 2017, Marceline Boyer was the top sales representative and Melanie Hayes was the most valuable customer. In 2018, leadership shifted, with Vanita Daniel becoming the top sales representative and Pamela Newman as the highest-revenue customer.
* **Dashboard Interactivity:** The deployment of interconnected slicers in Excel and action filters in Tableau successfully allowed executive end-users to isolate performance metrics down to individual stores (e.g., Baldwin Bikes vs. Rowlett Bikes) and specific years without requiring database queries.

## Results
* **Dual Dashboard Deployment:** Successfully built and deployed two distinct, interactive executive dashboards (Excel and Tableau) from a single SQL-generated dataset.
* **Self-Service Business Intelligence:** Transformed scattered relational database tables into an accessible analytics tool. Executives can now instantly filter KPIs across multiple dimensions (Year, State, Store) using interconnected slicers and action filters without requiring new database queries.
* **Comprehensive KPI Tracking:** The final deliverable provides a clear, highly visual summary of critical metrics, tracking total revenue breakdowns by region, store, brand, and individual sales representative performance.
