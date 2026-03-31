# E-Commerce Funnel Revenue Analysis Using SQL

Summary:
This project analyzes user behavior across an e-commerce funnel to identify drop-off points, conversion performance, and revenue opportunities. Using SQL, I calculated funnel stages, conversion rates, traffic source performance, and time-to-conversion metrics. The analysis revealed that while the checkout process is highly efficient, significant user drop-off occurs earlier in the funnel, and marketing channels vary greatly in effectiveness. These insights were used to generate actionable recommendations to improve conversions and revenue.

Business Problem:
E-commerce businesses often struggle to understand where users drop off in the purchase journey and which marketing channels drive the most value. Without this insight, teams may invest in low-performing channels or optimize areas that are already efficient. This project aims to identify inefficiencies in the funnel and highlight opportunities to increase conversions and revenue.

Methodology:
1. Used SQL queries to extract and aggregate user event data across key funnel stages.
2. Calculated conversion rates between each stage of the funnel to identify drop-offs.
3. Analyzed performance by traffic source to compare conversion efficiency across channels.
4. Measured time between user actions to understand how quickly users convert.
5. Built revenue metrics including average order value and revenue per user.

Skills:
1. SQL: CTEs, joins, CASE statements, aggregate functions, window functions
2. Data Analysis: Funnel analysis, conversion rate calculation
3. Business Analytics: KPI development, performance analysis, revenue insights

Key findings:
1. The funnel starts with ~5000 users and ends with ~826 purchases (~17% overall conversion rate).
2. The largest drop-off occurs between page view and add-to-cart, indicating early-stage friction.
3. The checkout process performs very well (~80%+ conversion), suggesting minimal issues in payment flow.
4. Email traffic has the highest conversion rate, while social media drives high traffic but low conversions.
5. Average Order Value (AOV) is approximately $100–$115, with total revenue around $88K.

Recommendations:
1. UX & Website Optimization: The largest drop-off happens before users add items to the cart.
2. Reduce spending on social media ads since they drive high traffic but low conversion rates.
3. Shift marketing efforts toward retargeting or lead generation to capture users who are not ready to purchase immediately.
4. Increase investment in email marketing because it delivers the highest conversion rates and the strongest return on investment.

