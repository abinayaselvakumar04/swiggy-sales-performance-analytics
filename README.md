Overview

This repository contains a Power BI report that consolidates order-level sales data into a single interactive dashboard. It is designed to help business stakeholders monitor overall profitability, identify high-performing cuisines and cities, understand delivery time impact on customer satisfaction, and analyze payment method trends.

Key Metrics Tracked


Sum of Profit – Total profit generated across all orders
Sum of Cost – Total operational cost across all orders
Final Sales Amount by Cuisine – Revenue breakdown across cuisine categories such as South Indian, Chinese, Italian, Fast Food, and North Indian
Average Final Sales Amount by City – Geographic performance visualized on a map
Final Sales Amount by Order Date – Daily sales trend over the reporting period
Customer Rating and Order Count by Cuisine and Delivery Time – Correlation between delivery speed and customer satisfaction
Order ID by Payment Mode – Distribution of orders across UPI, Credit Card, Debit Card, Cash, and Wallet


Dashboard Features


Interactive slicers for Payment Mode and Cuisine to filter the entire report
Drill-down capable visuals for time-series and category-based analysis
Geographic mapping of sales performance by city
Scatter plot analysis correlating delivery time with customer ratings and order volume
Donut chart representation of payment mode distribution


Data Fields Used

FieldDescriptionOrderIDUnique identifier for each orderOrderDateDate on which the order was placedCuisineCategory of food orderedCityDelivery cityFinalSalesAmountNet sales value of the orderCostCost incurred for fulfilling the orderProfitProfit earned per orderDeliveryTimeTime taken to deliver the order (in minutes)CustomerRatingRating given by the customer post-deliveryPaymentModeMode of payment used (UPI, Cash, Wallet, Credit Card, Debit Card)

Tools Used


Power BI Desktop – Report design and DAX-based calculations
Power Query – Data cleaning and transformation
DAX – Measures for profit, cost, and aggregated KPIs


How to Use


Clone or download this repository.
Open the .pbix file in Power BI Desktop.
Refresh the data source if connected to a live dataset.
Use the slicers on the right panel to filter by Payment Mode or Cuisine.
Hover over visuals for tooltips with detailed breakdowns.


Potential Future Enhancements


Add year-over-year comparison metrics
Include delivery partner performance analysis
Incorporate customer segmentation and repeat order analysis
Add forecasting for future sales trends


License

This project is intended for educational and portfolio demonstration purposes.

Author

Prepared as part of a data analytics portfolio project focused on food delivery business intelligence reporting.
