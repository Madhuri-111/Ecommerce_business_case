<h1>Ecommerce business case summary  </h1>

<h3>Data Description: </h3>
Transaction data has been provided from 1st Jan 2019 to 31st Dec 2019. 
The datasets below have been provided:

Online_Sales.csv: This file contains actual orders data (point of Sales data) at the transaction level with the following variables.
1.	CustomerID: Customer unique ID
2.	Transaction_ID: Transaction Unique ID
3.	Transaction_Date: Date of Transaction
4.	Product_SKU: SKU ID – Unique Id for product
5.	Product_Description: Product Description
6.	Product_Cateogry: Product Category
7.	Quantity: Number of items ordered
8.	Avg_Price: Price per one quantity
9.	Delivery_Charges: Charges for delivery
10.	Coupon_Status: Any discount coupon applied

Customers_Data.csv: This file contains customer’s demographics.
1.	CustomerID: Customer Unique ID
2.	Gender: Gender of the customer
3.	Location: Location of Customer
4.	Tenure_Months: Tenure in Months

Discount_Coupon.csv: Discount coupons have been given for different categories in different
months
1.	Month: Discount coupon applied in that month
2.	Product_Category: Product category
3.	Coupon_Code: Coupon Code for the given Category and the given month
4.	Discount_pct: Discount Percentage for the given coupon

Marketing_Spend.csv: Marketing spend on both offline & online channels on day day-wise.
1.	Date: Date
2.	Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, hoardings, etc.
3.	Online_Spend: Marketing spend on online channels like Google keywords, Facebook, etc.

Tax_Amount.csv: GST Details for given category
1.	Product_Category: Product Category
2.	GST: Percentage of GST


<h3>Business question addressed with logics and calculations used: </h3>

<h4>1.Identify the months with the highest and lowest acquisition rates. What strategies could be implemented to address the fluctuations and ensure consistent growth throughout the year?</h4>
For each month, calculated the number of first purchases for every customer using the file online_sales.csv. </br>
Below is the bar garph representing the same: </br>
![image](https://github.com/user-attachments/assets/6e714a4c-5d0a-4961-a7ad-b95138507ff2)

<h5>Insights:</h5>

Heighest Acquisition: January

Lowest Acquisition: November

<h5>Strategies to Address Fluctuations & Ensure Consistent Growth:</h5>

For Low-Acquisition Months (like November and December): </br>
Holiday Campaigns & Discounts: Leverage the festive season to offer attractive bundles or exclusive deals.</br>
Content Push: Publish high-traffic blog posts, reels, or educational content to maintain visibility.</br>
Partnerships & Affiliates: Use affiliates or micro-influencers to reach wider audiences.</br>

For High-Acquisition Months (like January):</br>
Double Down on What Works: Analyze what campaigns performed well and scale them.</br>
Enhance Onboarding: Ensure users acquired convert to active, loyal customers.</br>
Referral Incentives: Encourage new users to bring others.




