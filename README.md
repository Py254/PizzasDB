# PizzasDB: SQL Database Exploration and Dashboard Analysis
**PizzasDB** is an SQL-based database exploration project to analyze sales and operational data from a pizza shop. The goal is to uncover key business insights, improve decision-making, and optimize operations. The project uses SQL to perform in-depth analysis on the dataset and Excel for creating an interactive dashboard summary that highlights trends, performance metrics, and actionable recommendations for business improvements.

- Table of Contents
- Project Overview
- Data Sources
- Project Structure
- Setup
- Analysis
- SQL Queries
- Excel Dashboard
- Results and Recommendations
- Acknowledgments

### Why the project is useful:
This project is useful because it enables the pizza shop to leverage data for better decision-making. By analyzing the dataset, the shop can uncover valuable insights like peak order times, popular pizza choices, delivery efficiency, and customer behavior patterns. With this information, the business can improve its customer service, streamline operations, forecast demand, and even create targeted marketing campaigns to increase sales.

### Data Sources
The dataset used for this project is sourced from a comprehensive Pizza Shop Dataset containing information on:

- **Sales Data**: Order volume, revenue, and sales figures.

- **Customer Data**: Demographics, preferences, and repeat purchase behavior.

- **Operational Data**: Delivery times, order fulfillment times, and inventory usage.

All data set info in the link below:
https://drive.google.com/drive/folders/1ecpBALfFUMSK-GOnk-X4nZhC_uK18zih

### Project Structure

 PizzasDB/

│

├── data/

│   └── pizzas_data.csv    https://drive.google.com/drive/folders/1ecpBALfFUMSK-GOnk-X4nZhC_uK18zih       

│

├── sql_queries/

│   ├── data_cleaning.sql           

│   ├── analysis_queries.sql  https://docs.google.com/document/d/1Xh7yenE10tF9p-J5_OrFaxRwrBFFOvXBRzwiYvLUfww/edit?tab=t.0

│

├── dashboard/

│   └── pizzas_dashboard.xlsx  (Attached in uploads)

### Analysis
### SQL Queries and Excel Dashboard
The analysis process begins by querying the database using SQL. The key queries focus on:

**Order Volume and Sales Analysis:**
Total orders and revenue over time (monthly/weekly/daily breakdowns).
Most and least popular pizza types based on sales volume.
Identifying peak sales periods to understand high-demand times.

**Customer Behavior:**
Customer segmentation based on order preferences.

### Key Performance Indicators (KPIs): 

- Such as total sales, average order value, and total sales.

- Trends & Insights: Monthly and weekly trends for order volume.

- Charts & Graphs: Visual representation of popular pizza types, peak order times.

- Recommendations: Based on the analysis, the dashboard provides actionable insights for improving business operations.

For further insights into the data provided, the results of the SQL queries are summarized and visualized in the Excel dashboard:

*i) To identify any patterns in order volumes on a daily basis - Daily trend for total orders*

*ii) To identify peak hours or periods of high order activity- Hourly trend for total orders*

*iii) To provide insight into the popularity of various pizza categories- Percentage of sales by pizza category*

*iv) Percentage of sales by pizza size*

*v) Total pizzas sold by pizza category*

*vi) Top 5 best sellers by total pizzas sold*

*vii) Bottom 5 sellers by total pizzas sold*

### Results and Recommendations

**Key Insights:**

1. Peak Sales Periods:

The analysis shows that the pizza shop experiences peak order volume during weekends, particularly on Fridays and Saturdays between 6-8 PM.
Implementing strategies for handling high demand during these periods could improve efficiency and customer satisfaction.

2. Popular Menu Items:

The top-selling pizzas are Margherita and Pepperoni. Expanding the menu with similar flavors or promotions could increase sales.

### Recommendations:
- Optimize Staffing: Increase staff during peak times to reduce order fulfillment and delivery delays.
- Targeted Marketing: Create marketing campaigns based on popular pizza items and high-demand periods.
- Customer Loyalty Programs: Introduce rewards or discounts for repeat customers to boost retention.

### Acknowledgments

Thanks to the *Pizza Shop Dataset* from www.youtube.com/@datatutorials1 for providing the raw data.

Special thanks to the SQL and Excel communities for helpful resources and tutorials that made this project possible.
