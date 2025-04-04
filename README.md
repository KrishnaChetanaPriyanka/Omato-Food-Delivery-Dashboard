# Omato Food Delivery Dashboard
This project presents a Power BI dashboard that provides insights into food delivery transactions, payment methods, food preferences, and order trends. The data has been analyzed and visualized to help understand customer behavior, top-selling food items, and transactional trends.

## Features
- 📊 Total Quantity & Transactions Overview
- 📆 Monthly Sales Performance
- 🍽️ Food Type & Member Type Analysis
- 💳 Transactions by Payment Method (UPI, COD, Card)
- 🚚 Delivery Status Breakdown (Delivered vs. Canceled)
- 📈 Food Item Popularity

## Data Sources
The data comes from January to April 2023 food delivery transactions, stored in multiple Excel files:
- 📂 January_Sales_2023.xlsx
- 📂 February_Sales_2023.xlsx
- 📂 March_Sales_2023.xlsx
- 📂 April_Sales_2023.xlsx
- 📂 Omato_Data.xlsx

## Power Query for Data Transformation
Power Query was used to clean and transform the raw datasets before loading them into Power BI. The key steps included:
- ✅ Merging and Appending Data – Combined sales data from different months into a single dataset.
- ✅ Data Cleaning – Removed duplicates, handled missing values, and ensured data consistency.
- ✅ Column Transformation – Extracted useful information such as month and year from date columns.
- ✅ Data Formatting – Changed data types for better performance in Power BI.

## Data Modeling
A star schema approach was used for efficient querying and analysis. The key relationships include:
- Fact Table: Sales_Transactions (stores all transaction details like food items, payment methods, and quantities).

#### Dimension Tables:
- Date_Dim (to analyze trends over time).
- Food_Dim (for food category-wise analysis).
- Payment_Method_Dim (to categorize payment modes).
- Customer_Type_Dim (to differentiate between Gold and Regular members).
- DAX Functions and Measures Used

## 🛠️ Software Used
- 📄 Microsoft Excel – Data Cleaning and Preprocessing
- 📊 Power BI – Data Visualization and Dashboard Creation

## Data Visualizations in Power BI
To make insights more accessible and visually appealing, multiple Power BI charts were implemented:
### Charts & Graphs Used
- 📊 Bar Chart: Displays total quantity sold per month.
- 📈 Line Graph: Tracks transaction trends over months.
- 📌 Stacked Bar Chart: Shows payment method preferences (UPI, COD, Card).
- 📑 Matrix Table: Displays food type vs. member type transactions.
- 📍 Donut Chart: Highlights delivered vs. cancelled orders.

## 📌 Repository Highlights
![image](https://github.com/user-attachments/assets/cbe743da-46e1-496e-8c17-41ee5f7fdf14)

## Key Insights from the Dashboard
- 🔹 Most Popular Food Item: Samosa (2,427 orders), followed by Butter Chicken (2,044 orders).
- 🔹 Peak Sales Month: February 2023 (4.4K items sold).
- 🔹 Most Preferred Payment Method: UPI (1,719 transactions).
- 🔹 High Delivery Success Rate: 94.25% of orders were delivered successfully.

## Conclusion & Future Recommendations
The Power BI dashboard provides valuable insights into customer preferences, sales trends, and delivery performance.
### Future Enhancements:
- ✅ Predictive Analytics – Implement time-series forecasting for future sales trends.
- ✅ Customer Segmentation – Identify high-value customers based on purchase behavior.
- ✅ Automated Data Refresh – Connect Power BI to SQL Server for real-time updates.

By implementing these improvements, we can enhance business decision-making and drive data-driven strategies.

Thank you for taking the time to review my submission!

😄
