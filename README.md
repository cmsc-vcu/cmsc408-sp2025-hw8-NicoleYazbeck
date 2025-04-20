# Homework 8 - World Bank Indicator Analysis

This project presents an SQL-based exploration and analysis of the World Bank wdi_country dataset. The goal is to understand the global distribution of countries by region and income group, and extract insights from country-level metadata.

## Dataset Overview

The dataset used is world_bank_data.wdi_country, which contains metadata about countries and non-country entities tracked by the World Bank. Some key columns include:

*  Country Code

*  Short Name

*  Long Name

*  Region

*  Income Group

*  Currency Unit

*  2-alpha code

*  WB-2 code

Other socio-economic and data availability indicators

## Key Analyses

*  ✔️ Record Counts & Data Exploration

*  ✔️ Filtering by Region & Income Group

*  ✔️ Comparing Country Codes

*  ✔️ Pivoting Data for Region-Income Breakdown

*  ✔️ Calculating Percentage Distributions

*  ✔️ Identifying Outliers or Data Issues

## Redering Report Using Quarto

  1. Open a terminal 
    
  2. Run the following command:

    quarto render reports/report.qmd

  3. This will generate the HTML file:
    
    .\report.html

## Tools Used 

*  SQL 

*  Data source: World Bank Open Data (world_bank_data.wdi_country)







