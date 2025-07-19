# Bike-Stote-Data-Analysis (Dashboard Using Tableau)
## Dataset Used
<a href=" https://github.com/Mohammad-Bilal554/Bike-Stote-Data-Analysis/blob/main/BikeStores.xlsx"> Dataset </a>
## Analysis Goals
The analysis aims to:
<ul>
<li>What is the total revenue generated during the available time period?</li>

<li>Which states contributed the most to overall revenue?</li>

<li>Which products and categories were the most popular (by units sold)?</li>

<li>Which brands generated the highest revenue?</li>

<li>How is revenue distributed across different product categories?</li>
</ul>

## Dashboard Interaction
<a href="https://github.com/Mohammad-Bilal554/Bike-Stote-Data-Analysis/blob/main/Dashboard.png"> View Dashboard </a>

## Process

<ul>
  
<li>
  
#### Data Loading

Read the Excel file using pandas.ExcelFile

Extract data from the Query1 sheet. </li>
<li>

#### Data Exploration

Inspected columns, data types, and null values

Identified date range and unique product details   </li>
<li>
  
#### Data Aggregation & Grouping

Grouped revenue by state, brand_name, category_name

Counted units sold by product_name   </li>
<li>
  
#### Insight Extraction

Sorted and visualized top contributors to revenue and sales

Calculated total revenue and summarized top performers  </li>
</ul>

## Dashboard
<img src="https://raw.githubusercontent.com/Mohammad-Bilal554/Bike-Stote-Data-Analysis/refs/heads/main/Dashboard.png"></img>

## Key Insights

<UL>

<li> 
  
  #### Total Revenue (2016–2018): $8.57 million </li>

<li>  
  
  #### Top Revenue States:

New York – $5.82M

California – $1.79M

Texas – $962K  </li>

<li> 
  
  #### Best-Selling Products (by units):

Electra Cruiser 1 (24-Inch) – 296 units

Electra Townie Original 7D EQ – 290 units 

Electra Girl’s Hawaii 1 – 269 units  </li>

<li> 
  
  #### Top Brands by Revenue:

Trek – $5.12M

Electra – $1.34M

Surly – $1.06M  </li>

<li> 
  
  #### Revenue by Category:

Mountain Bikes – $3.03M

Road Bikes – $1.85M

Electric Bikes – $1.02M  </li>

</UL>

## Conclusion
The analysis reveals that New York dominates in revenue contribution, followed by California and Texas. Trek and Electra are leading brands, and mountain bikes are the top-performing category. This insight can help the fictional company allocate inventory, plan promotions, and expand in high-revenue regions.
