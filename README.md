## Key Findings from Data Exploration:
#Missing Values:
CustomerID, TransactionDate, PaymentMethod, StoreType, CustomerAge, CustomerGender, and ProductName have 50,000 missing values.
Region has 42,633 missing values.

##Transaction Analysis:
The average transaction amount is $20,405, with a maximum of $99,996 and a minimum of -$999, suggesting possible incorrect or refund transactions.
The average discount applied is 25%, with some transactions having a 50% discount.

#Customer Demographics:
The average customer age is 46 years, ranging from 18 to 74 years.
Gender information is missing for 50,000 customers.

#Shipping & Delivery:
Average shipping cost is $397, with some transactions having $0.
Delivery times range from 1 to 15 days, with an average of 5 days.
Next, I'll generate aggregate metrics and drill-down insights before providing SQL scripts. ​​

#Key Insights:
Total Sales & Quantity:
Total Revenue: $10.2 billion
Average Transaction Value: $20,405
Total Items Sold: 3.75 million units

#Sales by City:
Top 3 cities by revenue: Kolkata ($1.03B), Ahmedabad ($1.02B), Bangalore ($1.02B)

#Store Type Performance:
Online vs. In-Store Sales:
In-Store Sales: $5.08 billion
Online Sales: $5.08 billion (Almost equal)

#Top Selling Products:
Laptop ($6.23B)
Sofa ($3.77B)
Other products contribute much less.

#Return Rate:
49.89% of transactions resulted in returns, which is very high.

#Delivery Performance:
Average delivery time is 5.2 days.

#Discount Impact:
Transactions are evenly distributed across discount ranges.
Highest sales in 30-40% discount range (~$2.05B).
