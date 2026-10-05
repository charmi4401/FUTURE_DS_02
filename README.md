# Customer Retention & Churn Analysis

## About This Project

This project looks at why customers leave and who is most likely to leave, using the Telco Customer Churn dataset. I wanted to find out which customer groups churn the most, how churn changes as customers stay longer, and what a business could realistically do to keep more of them.

## Tools Used

- Microsoft Excel
- Power BI

## Dataset

The data comes from the Telco Customer Churn dataset on Kaggle. It has 7,043 customer records covering demographics, services, contracts, payment methods, charges, tenure, and whether the customer churned.

## Key Numbers

- Total customers: 7,043
- Churned customers: 1,869
- Retained customers: 5,174
- Churn rate: 26.53%
- Retention rate: 73.47%
- Average tenure: 32.37 months
- Average monthly charges: 64.76

## What I Looked At

I broke churn down by:

- Contract type
- Customer tenure
- Internet service
- Payment method
- Monthly charges
- Senior citizen status
- Partner status
- Dependents

## What I Found

### Contract Type

Month-to-month customers are the most likely to leave, with a churn rate of 42.71%. Customers on one-year contracts churn at 11.27%, and those on two-year contracts at just 2.83%. Longer commitments clearly go hand in hand with staying.

### Customer Tenure

New customers are the most fragile. Those in their first 0-12 months churn at 47.44%. The longer people stay, the less likely they are to leave, and customers with 49+ months of tenure churn at only 9.51%.

### Internet Service

Fiber optic customers churn at 41.89%, which is more than double the 18.96% seen among DSL customers.

### Payment Method

Customers paying by electronic check have the highest churn rate of any payment method, at 45.29%.

### Monthly Charges

Customers paying 80 or more per month churn at 33.99%, compared with 15.74% for those paying under 50.

## Recommendations

1. Put more effort into onboarding and engagement during the first 12 months, when customers are most at risk.
2. Promote long-term contracts with real benefits so customers have a reason to commit.
3. Take a closer look at service quality, pricing, and support for the higher-risk groups.
4. Find out what the customer experience is like for electronic check payers.
5. Review pricing and perceived value for customers with higher monthly charges.
6. Focus retention efforts on customers who show several high-risk traits at once.

## Power BI Dashboard

The dashboard includes:

- KPI cards
- Churn rate by contract type
- Churn rate by customer tenure
- Churn rate by internet service
- Churn rate by payment method
- Churn rate by monthly charges
- Slicers for contract, internet service, payment method, and senior citizen status

The slicers let you filter the dashboard and explore the patterns yourself.

## Limitations

The dataset has no churn-reason field and no signup dates. Because of that, this project shows patterns and associations in churn, not proven causes. For the same reason, a classic signup-month cohort analysis wasn't possible, so tenure is used as a stand-in for customer lifetime.

## Project Files

- `Customer_Retention_Churn_Analysis.pbix` - the interactive Power BI dashboard
- `Customer_Retention_Churn_Analysis.xlsx` - the Excel analysis workbook
- `Insights_and_Recommendations.txt` - detailed insights and recommendations
- `README.md` - this documentation

## Conclusion

Churn is highest among month-to-month customers, newer customers, fiber optic users, electronic check payers, and customers with higher monthly bills. A subscription business can use these findings to decide where to focus first: better onboarding, stronger engagement, service improvements, and retention offers aimed at the customers most likely to leave.
