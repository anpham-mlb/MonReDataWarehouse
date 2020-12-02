## Introduction 
MonRE is an agency that help individuals withing Australia to find the most suitable properties around Australia. MonRE wants to build a data warehouse to keep
track of the real estate property related information, e.g. calculating statistics of rents and sales automatically which can later be used for forecasting various trends and making predictions about the real estate.

## Details
### Step 1
Build an ER diagram from collective information from MonRE (Figure 1).
### Step 2
Using SQL to explore and clean the operation database.
### Step 3 
Develop the star schema of real estate properties around Australia in two versions (level 2 and level 0) using SQL (Figure 2 and Figure 3).
### Step 4
Implement the two versions of star schema using SQL
### Step 5
Generate reports using OLAP queries

### Results
From the data warehouse, users are able to know information such as:
- What is the average rental fee of apartments around South Yarra, VIC in 2019?
- What is the average earning for all Ray White agents?
- What is the average sales for houses in VIC compared to NSW?
- Who are the top 3 agents in Melbourne?
- What is the total number of rent for clients who stay in small scale properties with very basic features?
- What is the total number of sales for Townhouses with Air Conditioning and Security?

From the OLAP reports, users are able to know information such as:
- What is the number of rents in 2019 and preceding two years?
- Show ranking of each property type based on the yearly total number of sales and the ranking of each state based on the yearly total number of sales.
- Show ranking of each property type based on the yearly total number of sales and the ranking of each state based on the yearly total number of sales with partition.
