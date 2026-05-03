# Hospitality Dataset (Raw Data)

## Dataset Overview
This folder contains the **raw hospitality dataset** used for analysis in Excel, MySQL, Power BI, and Tableau projects.

The data represents hotel bookings, room details, revenue, and occupancy, which is used to analyze business performance and customer trends.

## Purpose of Dataset
- Perform hospitality and booking analysis  
- Practice data cleaning and transformation  
- Build dashboards and reports  
- Write SQL queries for insights  
- Understand real-world business data 

## Files Included
- **dim_date.csv** → Date-related information  
- **dim_hotels.csv** → Hotel details  
- **dim_rooms.csv** → Room information  
- **fact_bookings.csv** → Detailed booking records  
- **fact_aggregated_bookings.csv** → Aggregated booking data 

## Dataset Description

### dim_date.csv (Date Information)
Contains date-related fields:

- Date  
- Day  
- Month  
- Year  
- Week Number  
- Quarter 

### dim_hotels.csv (Hotel Information)
Contains hotel details:

- Hotel ID  
- Hotel Name  
- City  
- Category (Luxury / Business, etc.) 

### dim_rooms.csv (Room Information)
Contains room-related details:

- Room ID  
- Room Type  
- Room Capacity  
- Price 

### fact_bookings.csv (Booking Data)
Contains detailed booking records:

- Booking ID  
- Hotel ID  
- Room ID  
- Check-in Date  
- Check-out Date  
- Number of Guests  
- Booking Status 

### fact_aggregated_bookings.csv (Aggregated Data)
Contains summarized booking data:

- Date  
- Hotel ID  
- Total Bookings  
- Revenue  
- Occupancy Rate 

## Data Preprocessing Notes
- Dataset may contain missing or null values  
- Data types (date, numeric) need validation  
- Duplicate records may exist  
- Relationships must be created between tables  
- Data cleaning is required before analysis 

## Data Usage
This dataset is used in the following projects:

-  Power BI Dashboard (Hospitality Analytics)  
-  Tableau Dashboard  
-  MySQL Analysis  
-  Excel Analysis  
