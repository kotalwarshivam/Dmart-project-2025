D-Mart Sales Dashboard Analysis
Overview
This project involves analyzing D-Mart's sales data for 2024. The insights cover sales performance by state, average district sales,
top stores by revenue, and contributions of product categories to overall revenue. The analysis process includes downloading data, transforming it, 
performing SQL preprocessing, and generating a clear Power BI dashboard.

Key Insights
      Sales Performance:
               Top States by Revenue: 
               Maharashtra, Gujarat, and Karnataka lead in sales.
               Top 5 Stores: 
      Highest-performing stores contribute significantly, led by Kerala with $629.7K in revenue.
Average District Sales: 
         Highlighted top districts like Bangalore ($6.0K) and Dehradun ($5.8K).
Product Categories:
Groceries contribute the most (21.98%), followed by Electronics (21.32%) and Clothing (19.82%).

Average Discount: 14.8%.
Total Revenue for 2024: $11.23M.
Average Daily Sales: $5.62K.
Average Sales Quantity per Order: 25 items.


Process Workflow
  1. Data Download
   Extracted raw sales data from the D-Mart Mention Dashboard.
   Data includes details on revenue, sales quantities, and product categories across states.

2. Data Transformation
       Cleaned and formatted data using Python (Pandas).
       Addressed missing values, standardized column names, and converted data types for consistency.
        Created calculated columns for metrics like average discount, daily sales, and contributions.

3. SQL Preprocessing
      Stored and preprocessed cleaned data in a relational database.
      Performed SQL queries for key calculations:
      Total revenue by state.
