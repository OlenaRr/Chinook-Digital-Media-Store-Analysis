# Chinook-Digital-Media-Store-Analysis

## Project Overview:
This project analyzes sales data to identify top-performing products, evaluate customer spend distribution, and assess employee sales performance to optimize operational strategies.

## Business Problem:
The goal is to understand revenue drivers, customer purchasing patterns, and geographic sales distribution in order to support marketing and catalog management decisions.

## Tools & Data:
​- **Data Source:** ([Chinook CSV Dataset](https://www.kaggle.com/datasets/anurag629/chinook-csv-dataset?select=Invoice.csv))

​- **Tools:** Python (DuckDB for SQL querying, Pandas for data extraction), Tableau (for visualization)

## Executive Summary (Key Insights):

- **Overall Sales Performance (2009–2013):**
During the analyzed period, the store generated $ 2,329 in total revenue across 412 purchases, driven by a base of 59 unique customers. 

- **Catalog Performance (Top Sellers):**
Top Genres: Rock ($ 827), Latin ($ 382), Metal ($ 261)
Top Albums/Collections: ‘Battlestar Galactica (Classic), Season 1’ ($ 36), ‘The Office, Season 3’ ($ 32), Minha Historia ($ 27)
Top Artists: Iron Maiden ($ 139), U2 ($106), Metallica ($90).

- **Customer Value & Pareto Analysis:**
Customer purchasing behavior is highly uniform, with total spend per customer narrowly clustered between $36.64 and $49.62. The classic 80/20 distribution is not observed. Instead, approximately 78% of customers (46 out of 59) generate 80% of total revenue.

- **Geography Performance:**
The USA is the dominant market, contributing 22.5% of global sales ($523) with the highest concentration of users (13 customers). The top markets (USA, Canada, France, Brazil, and Germany) generate higher revenue primarily due to a larger customer base, as average customer spend remains relatively consistent across countries.

- **Sales Rep Performance:**
 Only 3 out of 8 employees act as customer support reps. Revenue differences closely mirror differences in customer counts. Jane Peacock leads with 833 in revenue from 21 clients, but the average revenue per customer across all three reps is virtually identical (38.77–40.01).

## Visual Highlights:

[Tableau Visualization](https://public.tableau.com/app/profile/olena.riaba/viz/Chinookdatasetanalysis/SalesPerformanceOverview?publish=yes)

## Recommendations:
- **Focus to Customer Acquisition:**
 Because average order value (AOV) is nearly identical across all regions and sales reps, marketing efforts should prioritize customer acquisition efforts in proven high-volume markets such as the USA, Canada, and France.
- **Promote Top-Performing Content:**
Feature top-performing genres and artists more prominently in store promotions and recommendation sections.

## Limitations & Project Notes:
- **Artificial Dataset:**
 The Chinook database is a simulated dataset created for educational purposes. Because of this, customer spending behavior is artificially uniform (almost all customers spend between $37 and $50). Consequently, real-world retail patterns—such as a sharp 80/20 Pareto distribution or distinct customer segmentation—are flatter here than they would be in a live business environment.

