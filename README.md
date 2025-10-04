# Kelly’s Ice Cream Shop
## 🏦 Project Overview
This project analyzes transaction data from Kelly’s Ice Cream Shop to understand customer spending behavior and evaluate the impact of discounts. By examining transaction amounts and customer patterns, we aim to:
- Identify high-value customers
- Understand spending distribution
- Detect frequent buyers
- Find opportunities to optimize discounts and promotions
Source: Kelly’s Ice Cream Transactions (Google Drive)

## 🗂 Dataset Columns
- `customer_id`: Unique identifier for each customer
- `transaction_id`: Unique identifier for each transaction
- `amount`: Transaction amount 

## 📊 Exploratory Data Analysis (EDA) Ideas
1.Transaction Amount Distribution
- Objective: Understand typical transaction values and detect unusual spending.
- Method: Histogram or boxplot of amount.

2.Customer Spending Analysis
- Objective: Calculate total and average spending per customer.
- Method: Group by customer_id and aggregate amount.

3.Transaction Frequency
- Objective: Determine how often each customer makes purchases.
- Method: Count transaction_id per customer_id.

4.High-Value Customer Detection
- Objective: Identify top spenders for targeted promotions.
- Method: Rank customers by total spending.

## 🛠️ Tech Stack
- Programming Language: Python
- Libraries: Pandas, Matplotlib, Seaborn, NumPy
- Platform: Google Colab

## ✅ Conclusion
- Most customers spend moderately, but a few high-value and frequent buyers drive the majority of revenue.
- These insights help Kelly’s Ice Cream Shop refine discounts, build loyalty programs, and boost overall sales.
