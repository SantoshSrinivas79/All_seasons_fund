# All_seasons_fund

Objective and Key Result
•	Objective: Determine an asset allocation for my personal investment portfolio 
•	Key Result: Develop a model that consumes 5 securities based on Ray Dalio’s All Weather Fund guidance and then outputs the optimal asset allocation and tweak the allocation moving forward   

My Workflow
Here's a breakdown of the workflow I used to create the All Seasons Portfolio: 

1. Import the data of the stock prices using tq_get from tidyquant
2. Transform stock prices to returns using tq_transmute
3. Building a portfolio based on the allocation of Ray Dalio's All Weather Fund using tq_portfolio
4. Visualize returns and sharpe ratio with ggplot2
5. Visualize the investment growth of the portfolio based on a $10,000 investment
