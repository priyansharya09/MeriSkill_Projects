<h1>Project 1: Sales Data Analysis</h1>
<h3>Sales Data Analysis</h3>
This project aims to analyze sales data from an Excel file and generate some useful insights. The project consists of the following steps:

Import sales data from an Excel file named sales_data.xlsx into Power BI
Transform data by splitting order date and time into separate columns using the split column feature
Use delimiter space for splitting order date and time and rename the column to make it more readable
Use DAX query Weekdays = FORMAT('Sales Data'[Order Date.1],"dddd") to calculate weekdays from the order date
Use measures for Total Sales = SUM('Sales Data'[Sales]), Total Cost = SUM('Sales Data'[Price Each]), and Profit Margin = (([Total Sales]-[Total Cost])/[Total Sales])*100 to calculate total sales, total cost, and profit margin for each order
