Hotel Revenue Analysis using SQL and Power BI
Overview
This project leverages SQL and Power BI to analyze data from a hotel chain. The dataset includes information about hotel revenue, customer types, market segments, and other relevant factors. The primary goal is to answer key business questions and present meaningful insights to stakeholders.

Key Questions Explored:
Is the hotel revenue growing by year?
We analyze revenue trends over the years to understand growth patterns.
Should the hotels increase their parking lot size?
We explore guest trends related to personal cars.
What other trends can we identify in the data?
Focus areas include average daily rates (ADR) and seasonal patterns.
Methodology
1. Database Development
We set up a Microsoft SQL Server database to accommodate the provided dataset.
The data spans multiple years (2018, 2019, and 2020) and includes additional information on meal costs and market segments.
We imported the relevant data from Excel into the SQL database.
2. SQL Query Development
SQL queries were developed to extract necessary information.
We calculated revenue using the formula: (stays_in_weekend_nights + stays_in_week_nights) * adr.
The revenue was grouped by hotel type and year.
3. Power BI Integration
We connected Power BI to the SQL database.
Interactive visualizations were created to explore revenue patterns, market segments, and seasonal trends.
