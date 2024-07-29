# Pandas-Data-Science-Tasks

**Project Background**

This project involves analyzing 12 months of sales data from an electronics store using Python's Pandas and Matplotlib libraries. The data includes details such as the month, product type, cost, purchase address, and more. The objective is to answer various business-related questions by cleaning and exploring the data.

**Data Cleaning Tasks**

Before diving into the analysis, the data undergoes several cleaning steps:

Dropping NaN Values: Remove rows with missing values to ensure data integrity.
Conditional Row Removal: Eliminate rows based on specific conditions that may indicate errors or irrelevant data.
Changing Column Types: Convert column data types for accurate analysis (e.g., to_numeric, to_datetime).

**Data Exploration**

The cleaned data is then used to explore and answer the following high-level business questions:

Best Month for Sales: Identify which month had the highest sales and the total earnings for that month.
Top-Selling City: Determine which city had the highest product sales.
Optimal Advertising Times: Find the best times to display advertisements to maximize sales.
Products Sold Together: Identify products that are frequently purchased together.
Best-Selling Product: Determine which product had the highest sales and hypothesize reasons for its popularity.

**Methods Used**

To answer these questions, various methods from Pandas and Matplotlib are employed, including:

Concatenating CSV Files: Combine multiple CSV files into a single DataFrame using pd.concat.
Adding and Parsing Columns: Create new columns by parsing and manipulating existing data.
Applying Custom Functions: Use the .apply() method to apply custom functions across DataFrame elements.
Aggregate Analysis with Groupby: Perform group-based analysis to derive insights.
Data Visualization: Create bar charts and line graphs to visualize the results and provide clear answers to the business questions.
This project demonstrates how to leverage Pandas and Matplotlib to transform raw data into actionable business insights through a combination of data cleaning, exploration, and visualization techniques.
