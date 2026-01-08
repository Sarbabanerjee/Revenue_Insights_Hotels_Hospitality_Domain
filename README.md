# Revenue_Insights_Hotels_Hospitality_Domain
📌 Project Overview
This project focuses on providing data-driven revenue insights for AtliQ Grands, a luxury hotel chain in India. Facing a decline in market share and revenue due to strategic moves by competitors and ineffective decision-making, the management implemented a Business Intelligence solution using Power BI to regain their market position.

🏨 Business Problem
AtliQ Grands owns multiple five-star hotels across India but was losing revenue due to the lack of a centralized system to analyze booking data and pricing strategies. The goal of this project was to build a dashboard to track key performance indicators (KPIs) and help the Revenue Management team make informed decisions.

🛠️ Tech Stack
Tool: Power BI Desktop

Data Cleaning: Power Query

Data Modeling: Star Schema

Analysis: DAX (Data Analysis Expressions)

Domain: Hospitality (Revenue Management)

📊 Key Metrics (KPIs)
The project involves the implementation of over 26 measures, including:

Revenue: Total revenue realized from successful bookings.

RevPAR (Revenue Per Available Room): Measures the revenue generated per available room, regardless of whether it's occupied.

ADR (Average Daily Rate): The average price paid for rooms sold.

Occupancy %: The ratio of occupied rooms to total available rooms.

Realization %: Percentage of successful "checked-out" bookings over total bookings.

DSRN (Daily Sellable Room Nights): The number of rooms available to sell per day.

🏗️ Project Workflow
1. Requirement Gathering & Mockups
Collaborated with domain experts to understand business requirements and design a dashboard mockup that aligns with stakeholders' needs.

2. Data Transformation (Power Query)
Imported and cleaned data from multiple sources (Hotels, Rooms, Bookings, Dates).

Handled data types, promoted headers, and removed unnecessary columns.

Created custom logic to distinguish between Hospitality Weekends (Friday & Saturday) and Weekdays.

3. Data Modeling
Established a Star Schema with Fact and Dimension tables.

Created relationships between the date dimension, hotel metadata, room categories, and booking facts.

4. DAX Implementation
Developed Calculated Columns for time-based analysis (Week Number, Day Type).

Created Key Measures for complex business calculations like Week-on-Week (WoW) growth and trend analysis.

5. Dashboard Design
KPI Cards: For high-level executive summaries.

Slicers: Filters for City, Room Type, Month, and Week.

Trend Charts: Visualizations showing revenue trends over time.

Conditional Formatting: Visual cues for customer ratings and revenue performance.

💡 Business Insights
Dynamic Pricing Opportunity: Analysis revealed that AtliQ Grands uses flat pricing, missing out on revenue during peak days and weekends.

Rating Correlation: Identified a strong correlation between low customer ratings and high cancellation rates in specific cities.

Platform Performance: Identified which booking platforms provide the best realization rates and which ones contribute most to cancellations.
