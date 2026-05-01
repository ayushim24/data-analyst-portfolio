# Adventure Works Raw Dataset

## Overview
This folder contains the **raw Adventure Works dataset** used for sales analysis. The data is structured in multiple Excel files representing **dimension tables** and **fact tables**, which are used for building a star schema model.

These files serve as the foundation for analysis in **MySQL, Power BI, and Tableau**.

## Dataset Files

### Dimension Tables (Descriptive Data)

- **DimDate.xlsx**  
  Contains date-related information such as year, month, quarter, and day.

- **DimProduct.xlsx**  
  Includes product details like product name, category, and attributes.

- **DimProductCategory.xlsx**  
  Stores high-level product categories.

- **DimProductSubCategory.xlsx**  
  Contains sub-category details linked to product categories.

- **DimSalesTerritory.xlsx**  
  Provides region and territory-related information.

- **DimCustomer.xlsx**  
  Contains customer details such as demographics and location.

### Fact Tables (Transactional Data)

- **FactInternetSales.xlsx**  
  Main sales dataset containing transaction-level records such as sales amount, quantity, and order details.

- **Fact_Internet_Sales_New.xlsx**  
  Updated or cleaned version of the sales dataset used for analysis and dashboarding.

## Purpose of Dataset
- Perform **sales and profit analysis**  
- Build relationships between tables using keys  
- Create a **star schema data model**  
- Enable efficient querying and reporting  

## Data Preparation Steps
- Handling missing/null values  
- Removing duplicate records  
- Standardizing column names  
- Creating relationships between tables  
- Converting data types for analysis  

## Usage in Project
- Imported into **MySQL** for SQL queries  
- Used in **Power BI** for dashboard creation  
- Connected to **Tableau** for visualization  

## Data Model
- **Fact Table:** FactInternetSales  
- **Dimension Tables:** Date, Product, Customer, Territory, Category  
- Relationships created using primary and foreign keys  

## Skills Demonstrated
- Data Understanding  
- Data Cleaning  
- Data Modeling (Star Schema)  
- Data Preparation for BI Tools  
