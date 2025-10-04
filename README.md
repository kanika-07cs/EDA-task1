# Kelly’s Ice Cream Shop
## 🏦 Project Overview
This project analyzes transaction data from Kelly’s Ice Cream Shop to understand customer spending behavior and evaluate the impact of discounts. By examining transaction amounts and customer patterns, we aim to:
- Identify high-value customers
- Understand spending distribution
- Detect frequent buyers
- Find opportunities to optimize discounts and promotions
  
Source: [Kelly’s Ice Cream Transactions (Google Drive)](https://drive.google.com/file/d/14sFXsZI6fdFhuxVD4EFOx39ac9WUfJOl/view?usp=sharing)

## 🗂 Dataset Columns
- `customer_id`: Unique identifier for each customer
- `transaction_id`: Unique identifier for each transaction
- `amount`: Transaction amount 

## 📊 Exploratory Data Analysis (EDA) Ideas
1 Data Understanding (Pandas)
- Load CSV into DataFrame and preview first 10 rows
- Check shape, columns, data types, missing values, and duplicates

2 Exploratory Data Analysis (EDA)
- Count transactions per customer
- Find each customer’s 3rd transaction
- Identify transactions with 33% discount
- Plot histograms for original and discounted 3rd transactions

3 Statistics
- Calculate average purchase and discounted amount
- Find probability that a random transaction is a discounted 3rd purchase

4 Feature Engineering
- Add columns: Transaction_Rank, Discount_Applied, Discounted_Amount, and Savings

5 Insights
- Identify top spender and customer with largest discount

## 🛠️ Tech Stack
- Programming Language: Python
- Libraries: Pandas, Matplotlib, Seaborn, NumPy
- Platform: Google Colab

## ✅ Conclusion
- Most customers spend moderately, but a few high-value and frequent buyers drive the majority of revenue.
- These insights help Kelly’s Ice Cream Shop refine discounts, build loyalty programs, and boost overall sales.
