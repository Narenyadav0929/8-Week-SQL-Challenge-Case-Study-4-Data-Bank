📊 8-Week SQL Challenge – Case Study #4: Data Bank
This repository contains my solutions for Case Study #4 - Data Bank from the 8-Week SQL Challenge. The case explores customer transaction behavior and data management strategies for a digital banking platform.

🗃️ Contents
Customer_nodes_exploration.ipynb – Solutions to Part A: Customer Nodes Exploration

Customer_transactions.ipynb – Solutions to Part B: Customer Transactions

README.md – This project overview

✅ Case Study Breakdown
🧩 A. Customer Nodes Exploration
This section investigates how customers are assigned to different data nodes and how their allocation changes over time.

Key questions explored:

How many unique nodes exist?

Node distribution by region

Number of customers per region

Average and percentile statistics on customer reallocation durations

💳 B. Customer Transactions
This section focuses on analyzing customer transaction behavior including deposits, withdrawals, and purchases.

Key questions explored:

Count and total amount of each transaction type

Historical deposit activity

Monthly customer behavior with multi-activity conditions

Monthly closing balances and growth rates

🧹 Data Cleaning
To ensure accurate insights, the following data-cleaning step was performed:

Removed all records with the placeholder date 9999-12-31, which likely represented missing or default values.

📌 Key Insights
Identified 10 unique customer nodes and mapped their regional distribution to understand customer allocation density.

Found that the average reallocation period varies by region, with some regions experiencing longer retention.

Observed that transaction types are unevenly distributed, with deposits forming the bulk of activity.

Detected a segment of customers who made multiple deposits and either a purchase or withdrawal in the same month — likely power users.

Measured monthly closing balances and found a portion of customers with over 5% increase, indicating active saving behavior.

🛠️ Tools Used
MySQL Server – SQL querying and logic development

Jupyter Notebook – Interactive exploration and documentation

Git & GitHub – Version control and portfolio presentation

Markdown – Case study formatting

📚 About the Challenge
This challenge is part of the 8-Week SQL Challenge designed by Danny Ma, offering real-world business problems and dataset analysis opportunities for aspiring data analysts and engineers.

📥 Getting Started
To explore this project:

Clone the repository.

Open the notebooks in a Jupyter environment.

Review each SQL query and explanation.
