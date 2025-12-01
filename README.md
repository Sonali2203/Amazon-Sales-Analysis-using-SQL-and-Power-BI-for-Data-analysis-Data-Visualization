# Amazon-Sales-Analysis-using-SQL-and-Power-BI-for-Data-analysis-Data-Visualization
# Amazon-Sales Analysis & Dashboard

## 📊 Project Overview  
This project analyses sales data from three branches of an Amazon store (Mandalay, Yangon, Naypyitaw) to uncover insights around products, sales trends, customer behaviour, and profitability.  
Using SQL for data processing / analysis, and Power BI for data visualization, the goal is to answer business questions such as: which product line performs best, which city generates highest sales, what times of day or months are most profitable, customer-segment profitability, and more.  

## 🧰 Data Description  
| Column | Description | Data Type |
|--------|-------------|------------|  
| invoice_id | Invoice identifier | VARCHAR(30) |  
| branch | Branch code (Mandalay / Yangon / Naypyitaw) | VARCHAR(5) |  
| city | City name of branch | VARCHAR(30) |  
| customer_type | Type of customer | VARCHAR(30) |  
| gender | Gender of customer | VARCHAR(10) |  
| product_line | Product line sold | VARCHAR(100) |  
| unit_price | Price per unit | DECIMAL(10,2) |  
| quantity | Units sold | INT |  
| VAT | VAT amount | FLOAT |  
| total | Total bill amount | DECIMAL(10,2) |  
| date | Date of transaction | DATE |  
| time | Timestamp of sale | TIMESTAMP |  
| payment_method | Payment method used | VARCHAR / DECIMAL |  
| cogs | Cost of Goods Sold | DECIMAL(10,2) |  
| gross_margin_percentage | Gross margin % for transaction | FLOAT |  
| gross_income | Gross income (profit) per transaction | DECIMAL(10,2) |  
| rating | Customer rating of purchase | FLOAT(2,1) |  

**Total rows:** 1000  
**Branches / Cities involved:** Mandalay, Yangon, Naypyitaw  


## 🚀 What the Project Does / Analysis Performed  

- Product analysis: Identify all product lines, determine top & under-performing product lines.  
- Sales trend analysis: Track monthly and branch-wise revenue, peak months, peak cities, sales-time-of-day & weekday trends.  
- Customer analysis: Segment customers by type, gender, city — analyze which segments contribute most revenue, frequency, profit, etc.  
- Profitability analysis: Calculate gross profit, gross margin %, cost-of-goods sold over time / per product / per branch / per customer segment.  
- Feature engineering: Created new fields:  
  - `timeofday` — marks sale as Morning / Afternoon / Evening  
  - `dayname` — day of the week for each sale  
  - `monthname` — month name of the sale  
- Business-questions answered:
- What is the count of distinct cities in the dataset?

For each branch, what is the corresponding city?

What is the count of distinct product lines in the dataset?

Which payment method occurs most frequently?

Which product line has the highest sales?

How much revenue is generated each month?

In which month did the cost of goods sold reach its peak?

Which product line generated the highest revenue?

In which city was the highest revenue recorded?

Which product line incurred the highest Value Added Tax?

For each product line, add a column indicating "Good" if its sales are above average, otherwise "Bad."

Identify the branch that exceeded the average number of products sold.

Which product line is most frequently associated with each gender?

Calculate the average rating for each product line.

Count the sales occurrences for each time of day on every weekday.

Identify the customer type contributing the highest revenue.

Determine the city with the highest VAT percentage.

Identify the customer type with the highest VAT payments.

What is the count of distinct customer types in the dataset?

What is the count of distinct payment methods in the dataset?

Which customer type occurs most frequently?

Identify the customer type with the highest purchase frequency.

Determine the predominant gender among customers.

Examine the distribution of genders within each branch.

Identify the time of day when customers provide the most ratings.

Determine the time of day with the highest customer ratings for each branch.

Identify the day of the week with the highest average ratings.

Determine the day of the week with the highest average ratings for each branch.


