# Zomato Sales Analysis - Power BI Project **[https://app.powerbi.com/groups/me/reports/bf1aa259-179c-45b7-85dd-5dc06c557f77/616d63ceec7fa4eafdd2?experience=power-bi]**

## Overview
This Power BI project provides an in-depth analysis of Zomato's sales and operational data. The goal is to help stakeholders make data-driven decisions by offering actionable insights into customer behavior, restaurant performance, menu trends, and order metrics.

## Features
- **Interactive Dashboards**: Easily explore key insights through dynamic visualizations.
- **Key Metrics and KPIs**: Track essential metrics like total sales, top-performing restaurants, and user activity.
- **Order Trends**: Understand ordering patterns, peak times, and delivery performance.
- **Menu Analysis**: Evaluate the popularity of menu items and their contribution to revenue.
- **Geographical Insights**: Analyze restaurant and order performance across different locations.

## Data Source
This report is built using data from a **SQL database**.

- **Database Name**: zomato_sales_analysis
- **Tables Used**:
  1. **food**: Contains details about food items.
  2. **menu**: Includes menu-related data such as item prices and availability.
  3. **orders**: Tracks order details, including timestamps and order statuses.
  4. **restaurant**: Information about restaurants, including names, locations, and ratings.
  5. **users**: Customer information, including demographics and usage history.

## Audience
This Power BI report is designed for:
- **Management**: To monitor overall performance and identify areas of improvement.
- **Marketing Teams**: To tailor campaigns based on customer behavior and preferences.
- **Operations Teams**: To improve delivery times and enhance restaurant efficiency.

## Setup Instructions
1. **Requirements**:
   - Microsoft Power BI Desktop installed.
   - Access to the `zomato_sales_analysis` SQL database.
2. **Steps**:
   - Open the `.pbix` file in Power BI Desktop.
   - Navigate to the "Transform Data" section to verify and configure the database connection.
   - Update the SQL server credentials and connection string if necessary.
   - Refresh the data to ensure the latest data is loaded into the report.

## Key Dashboards and Insights
1. **Sales Overview**:
   - Total revenue and sales trends over time.
   - Breakdown of sales by restaurant, menu item, and region.
2. **Customer Insights**:
   - Demographic analysis of users.
   - Analysis of customer ordering habits and retention rates.
3. **Order Performance**:
   - Order completion rates and delivery times.
   - Peak order times and seasonal trends.
4. **Menu Performance**:
   - Top-performing dishes and menu categories.
   - Revenue contribution of each menu item.
5. **Restaurant Analysis**:
   - Performance of individual restaurants based on revenue and user ratings.
   - Location-based performance trends.

## Known Limitations
- **Database Dependency**: The report requires a live connection to the `zomato_sales_analysis` database. Ensure database availability before refreshing the data.
- **Scalability**: Large datasets may impact performance during data refreshes or visualization rendering.

## Future Improvements
- Integration with real-time analytics for up-to-the-minute insights.
- Inclusion of customer feedback analysis for sentiment insights.
- Advanced predictive analytics to forecast trends and customer behavior.

## Contact
For questions or support, contact the project maintainer:
- **Name**: [VAIBHAV KHANDAVE]
- **Email**: [vaibhavkhandave123@gmail.com]

---

Feel free to contribute by suggesting improvements or raising issues.
