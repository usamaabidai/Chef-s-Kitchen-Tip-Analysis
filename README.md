# Chef's Kitchen Tip Analysis

## Project Overview
This project analyzes tipping patterns at Chef's Kitchen, a popular restaurant in San Diego. By examining customer data, bill amounts, and tipping behavior across various demographics, this analysis aims to identify key trends and insights that can help the restaurant understand customer spending habits and optimize service strategies.

## Dataset Description
The analysis is based on transaction data from Chef's Kitchen, containing the following features:
- **order_id**: Unique identifier for each order
- **day**: Day of the week (Thur/Fri/Sat/Sun)
- **time**: Time of day (Lunch or Dinner)
- **size**: Number of people at the table
- **smoker**: Whether the table included smokers (Yes/No)
- **sex**: Gender of the bill payer (Male/Female)
- **total_bill**: Bill amount in dollars
- **tip**: Tip amount in dollars

## Key Findings

### Billing and Tipping Patterns
- Bill amounts range from $3 to $50, with an average of approximately $20
- Tip amounts range from $1 to $10, with both mean and median around $3
- 50% of customers pay less than $20 for their total bill and less than $3 in tips
- There is a clear linear relationship between total bill amount and tip amount

### Time and Day Analysis
- Order volume is significantly higher on weekends compared to weekdays
- Dinner service generates more orders than lunch service
- Median bill amounts are higher on Saturdays and Sundays
- Median tip amounts are consistent on Friday, Saturday, and Sunday, but lower on Thursday
- Customers spend approximately $3 more during dinner ($19 median) compared to lunch ($16 median)
- Dinner tips average about $1 higher than lunch tips

### Demographic Insights
- Male bill payers (160) outnumber female bill payers (80) by a 2:1 ratio
- The gender disparity is most pronounced on weekends
- Median tip values are similar across genders, though male tippers show more variability with more outliers on the higher end
- Non-smoking tables outnumber smoking tables by approximately 60
- Non-smokers are significantly more common on Thursdays and Sundays
- Fridays are the only day when smokers outnumber non-smokers
- Smoking status does not appear to influence tip amounts

## Methods Used
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical analysis
- Data visualization
- Pattern recognition

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
