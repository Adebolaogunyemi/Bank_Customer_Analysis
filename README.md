# Bank_Customer_Analysis
Insight on how bank can improve customer retention strategies, optimize financial products, and better understanding of customer behavior across different segments.

Title

Customer Churn Analysis in Retail Banking: Data-Driven Insights and Strategic Recommendations

Problem Statement

Customer churn presents a significant challenge for banks, impacting long-term profitability and growth. A considerable portion of high-value customers is exiting without clear patterns, leading to increased customer acquisition costs and loss of potential lifetime value.

This project seeks to uncover the drivers behind customer churn and to support proactive strategies that improve retention, especially for high-value and at-risk segments.


Objective

Analyze bank customer data to identify patterns and key drivers of churn.

Segment customers based on behavior and value to understand retention opportunities.

Provide actionable recommendations to reduce churn and increase customer lifetime value.

Set the foundation for a predictive churn model using machine learning techniques.


Datasets Used

1. Customer_Info.csv
Contains demographic details:

CustomerID, Surname, Gender, Age, Geography

2. Account_Info.csv
Contains account-related details:

CreditScore, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Tenure, Exited (Churn Flag)

The datasets were merged on CustomerID for a unified view of each customer.


Approach

1. Data Collection & Cleaning
Two datasets (Customer_Info.csv and Account_Info.csv) were merged on CustomerId.

Cleaned and converted text-based numeric values (e.g. “€72,000”) into usable numeric format.

Removed missing and inconsistent values.

2. Exploratory Data Analysis
Analyzed churn patterns by:

Demographics (Age, Gender, Geography)

Account attributes (Balance, Credit Score, Products)

Engagement (Active Member, Credit Card ownership)

Created balance quartiles to segment customers into Low, Medium, High, and Very High tiers.

3. Segmentation

Grouped customers into balance quartiles: Low, Medium, High, Very High.

Compared churn across segments to identify at-risk groups.




Analysis and Insights

Key Findings:
 - Churn Rate: ~20.4% of customers have exited.

 - Age: Customers aged 40–60 are more likely to churn.

 - Geography: Germany has the highest churn rate.

 - Balance: Customers with high balances are more likely to churn, indicating a risk to revenue.

 - Number of Products: Those with only one product churn the most, while customers with 3+ products rarely churn.

 - Activity: Inactive members churn significantly more than active ones.

 - Gender: Slightly higher churn among female customers.


Conclusion

Churn is influenced not just by customer demographics but also by product engagement, activity level, and financial value. High-balance clients and inactive customers form the highest-risk groups, indicating that losing valuable customers is a significant business threat.


Recommendations

1. Retain High-Balance Clients
 - Offer loyalty benefits and exclusive services (e.g., wealth management).

 - Assign personal bankers to high-value clients.

2. Engage Inactive Users
 - Send re-engagement campaigns to customers inactive for over 3 months.

 - Use mobile/email alerts and tailored offers to reignite activity.

3. Promote Cross-Selling
 - Encourage customers to adopt more products through bundled offerings.

 - Use product recommendation engines to suggest next-best products.

4. Focus on German Region
 - Conduct root-cause surveys or feedback in the German segment.

 - Offer region-specific promotions or better customer service.

5. Tailor Services to Older Customers
  - Provide simplified digital tools, training, or phone support.

  - Market products relevant to this age group, such as retirement savings.









