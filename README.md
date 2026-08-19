# Uber_Data_Analyst_Power-BI
nteractive Power BI dashboard analyzing Uber ride bookings — revenue, cancellations, vehicle performance, profitability, geo coverage, and ratings — built on a single ncr_ride_bookings fact table.


📊 Project Description

This project is an end-to-end Power BI dashboard built on an Uber-style ride bookings dataset (ncr_ride_bookings). It turns raw trip-level records into a 5-page interactive report that surfaces booking trends, operational efficiency, profitability, geographic reach, and service quality — enabling quick, data-driven decisions on fleet and pricing strategy.

Report Pages
Page	Focus
Overall	Total bookings, booking value, cancellations by customer, and monthly booking trend
Vehicle Status	Ride status and average pickup/turnaround time (VTAT/CTAT) by vehicle type, plus revenue vs. target
Profit Stats	Revenue breakdown by payment method, revenue by vehicle type, and total profit vs. target (KPI)
Location Available	Pickup and drop-off location coverage on an interactive map
Ratings	Driver ratings vs. customer ratings by vehicle type
Key Metrics Modeled

Booking ID, Vehicle Type, Booking Status, Booking Value, Cancelled Rides by Customer, Ride Status, VTAT / CTAT (pickup & trip times), Payment Method, Total Profit, Target, Driver Rating, Customer Rating, Pickup/Drop Location, and Date (with month-level drill-down).

Visuals Used

Cards & KPIs, line chart, pie chart, bar chart, stacked area chart, tree map, column chart, gauge, table, map, and slicers — chosen to match each page's analytical question rather than reused generically.

Tech Stack
Power BI Desktop (.pbix) for data modeling and report authoring
Power Query for data shaping
DAX measures for KPIs (Total Profit, Targets, aggregations)
How to Use
Open Uber_Power_Bi_project.pbix in Power BI Desktop.
Refresh the data source if prompted.
Use the date and vehicle-type slicers on each page to filter the analysis.

A one-slide (A5) visual summary of this project is available as Uber_PowerBI_Summary_A5.pptx in this repo/attachment.
