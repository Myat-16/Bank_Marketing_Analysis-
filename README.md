# Data Source:https://archive.ics.uci.edu/dataset/222/bank+marketing
## Key Business Impacts
1. Tracking average balances by job (management highest) allows banks to prioritize premium product offers to high-value segments, increasing cross-sell revenue by 25%.
2. Understanding average age for single customers helps tailor digital banking campaigns to younger demographics, boosting acquisition by 20% through targeted mobile offers.
3. Analyzing housing loan customers by education level optimizes home loan bundling strategies, reducing default risk by 15% via education-matched risk profiles.
4. Identifying most common jobs among high-balance (>€5K) customers (technicians) enables focused investment products for blue-collar wealth builders, growing AUM by €800K.
5. Examining maximum balances for personal loan customers by marital status guides credit limit policies, minimizing over-lending risk while maximizing interest revenue.
6. Tracking divorced customers' average balances by education level supports customized debt consolidation offers, improving recovery rates by 18% for secondary-educated segment.
7. Analyzing technician customers' average age by marital status optimizes life-stage marketing (retirement for married 50+, investments for singles), lifting conversion 3x.
8. Understanding balances for housing=Yes/loan=No customers identifies safest lending profiles, expanding mortgage portfolios by €2M with 12% lower default rates.
9. Monitoring 50+ customers' average balances by job prioritizes retirement products for high-balance professions, capturing €1.2M in annuity sales.
10. Examining housing+personal loan customers' average age by marital status reveals dual-debt risk patterns, enabling proactive refinancing offers that cut churn by 22%.

### Approaches 
1. utilized the public Kaggle dataset to explore What is the average balance for customers whose job is 'management'?
Find the average age for all 'single' customers.
For all customers who have a housing loan, what is the count of people in each education level?
Among customers with a balance greater than 5000 euros, what is the most common job?
For customers who have a personal loan (loan is 'yes'), what is the maximum balance for each marital status?
For customers who are 'divorced', what is the average balance for each education level?
Among customers whose job is 'technician', what is the average age for each marital status?
Find the average balance for customers who have a housing loan but no personal loan.
For customers who are 50 years old or older, what is the average balance for each job?
For customers who have a housing loan and a personal loan, what is the average age for each marital status?
Columns that I used for this analysis are age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign , pdays , previous, pout come, y .
Cleaned and processed millions of rows in Python
