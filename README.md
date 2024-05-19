# Global-Super-Store-Sales-Analysis

As part of my Data Science and Machine Learning course at Entrí Elevate, I worked on a Power BI dashboard project. I had access to a dataset from a global supermarket chain with branches all over the world. The stakeholders requested a detailed report on their sales transactions.

The dataset consists of three main tables:

Global Superstore - Orders: This table contains 24 columns and 51,290 rows.

Global Superstore - People: This table contains 2 columns and 13 rows.

Global Superstore - Returns: Details related to product returns, this table contains 3 columns and 1173 rows.

Here’s how I approached the project:

Data Import and Transformation:
I imported the CSV-format table into Power BI.
Using the Power Query Editor, I transformed the tables to prepare them for analysis.
Specifically, I corrected the date formats for both order date and ship date, ensuring they were in the correct order.

Measures and Columns:
I created four essential measures:
Product Count: Calculated the total count of products sold.
Customer Count: Determined the number of unique customers.
Total Sales: Aggregated the overall sales revenue.
Total Profit: Calculated the net profit.

Additionally, I added two custom columns:
Days to Ship: Calculated the delivery time for each order using the DATEDIF function.
Profit or Loss: Used an IF function to determine whether a specific order resulted in profit or loss for the store.

Table Relationships:
I established relationships between the tables using the Model View. This allowed seamless navigation and data integration.

Dashboard Creation:
Finally, I designed an interactive dashboard that showcases key insights. You can see it here!
