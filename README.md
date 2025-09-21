Overview 📝 - 
​This project performs an exploratory data analysis (EDA) on the "Sample - Superstore" dataset. The primary goal is to uncover key performance indicators and insights related to sales, profit, and product categories. By analyzing sales patterns and the impact of discounts on profitability, this analysis provides actionable insights that can help guide business strategy.
​📊 Dataset
​The analysis is based on the Sample - Superstore.csv dataset, which contains transactional data for a US-based superstore. The dataset includes information on orders, shipments, products, customers, and sales figures.
​Source: Sample - Superstore.csv
​Time Period: 2014-2017
​Key Columns: Sales, Profit, Discount, Category, Sub-Category
​Analysis & Key Findings 💡
​This analysis focuses on four key business questions:
​1. What is the Total and Average Sale Value?
​To understand the overall business performance, the total and average sales were calculated across all transactions.
​Total Sales: The company generated a total of $2.3 million in sales.  
​Average Sale Value: The average value per transaction is approximately $229.86.
​2. Which Product Category is the Best-Seller?
​Sales were aggregated by product category to identify the top-performing segment.
​Best-Selling Category: Technology is the highest-grossing category, indicating it is a major driver of revenue for the business. Furniture and Office Supplies follow, respectively.
​3. What is the Relationship Between Discount and Profit?
​A correlation analysis was performed to understand the financial impact of offering discounts.
​Key Insight: There is a clear negative correlation between discount and profit. While small discounts (0-20%) can still result in profitable sales, higher discounts are strongly associated with a decrease in profit, often leading to a financial loss on the transaction.
​Recommendation: The company should re-evaluate its discount strategy, particularly for discounts exceeding 20%, to ensure sustainable profitability.
​🛠️ Tools & Libraries
```bash
git clone https://your-repository-url.git
```

​This analysis was conducted using Python and the following libraries:
​Pandas: For data manipulation and analysis.  
​Matplotlib & Seaborn: For data visualization and creating plots.
​Jupyter Notebook: As the primary environment for the analysis.
​How to Run the Analysis 🚀
​To reproduce this analysis, you will need to have Python and the libraries listed above installed.
