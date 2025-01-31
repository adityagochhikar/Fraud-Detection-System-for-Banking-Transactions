
# 📊 BankSim Fraud Detection Analysis

# 🎯 Objective

This project analyzes synthetic bank transaction data from the BankSim simulator to detect patterns and anomalies associated with fraudulent activities. Using Excel-based techniques, we clean, explore, and visualize the data to develop fraud detection strategies.

# 📂 Dataset Overview

📌 Source: BankSim (Simulated Bank Transactions from a Spanish Bank)

📌 Total Records: 594,643

📌 Normal Transactions: 587,443

📌 Fraudulent Transactions: 7,200 (≈1% of total transactions, indicating an imbalanced dataset)

# 🔑 Key Dataset Columns

step – Simulation time step

customer – Unique customer ID

age – Customer's age group

gender – Customer's gender

merchant – Merchant where the transaction occurs

category – Type of transaction

amount – Transaction amount

fraud – 0 (No Fraud) / 1 (Fraud)

# 🔄 Analysis Workflow

1️⃣ Data Cleaning – Remove duplicates, correct formats, and ensure data integrity.

2️⃣ Fraud Identification – Use filters & conditional formatting to highlight fraudulent transactions.

3️⃣ Pivot Table Analysis – Summarize fraud trends by step, customer, merchant, and category.

4️⃣ Visualization – Develop charts for fraud distribution, transaction patterns, and high-risk categories.

5️⃣ Insights & Interpretation – Identify key fraud trends & actionable strategies.

# 📊 Key Insights

📍 Fraud Distribution

🔹 Fraudulent transactions account for just 1% of total transactions, highlighting an imbalanced dataset.

📍 Age Group Analysis

✅ Fraud is heavily concentrated in younger age groups (0, 1, 2).

✅ Age groups 2 (184,966) & 3 (145,376) dominate normal transactions.

📍 Gender & Category Trends

✅ Fraud is significantly higher for Females ("F") with 4,758 cases compared to Males ("M") with 2,435 cases.

✅ Categories "es_health" (€664,804) & "es_sportsandtoys" (€505,311) have the highest fraud amounts.

✅ No fraud detected in the "es_transportation" category.

📍 Merchant Insights

✅ 43% of fraud cases are linked to M480139044 & M980657600.

📍 Transaction Amount Patterns

🔹 Fraudulent transactions are 10x-18x higher than normal transactions.

🔹 Peaks in fraud occur at:

Steps 25-49 (€588.5 avg fraud amount)

Steps 100-124 (€615.6 avg fraud amount)

🔹 Fraud declines in later steps (e.g., Steps 175-199: €414.4 avg).

# 🚀 Fraud Detection Strategy

🔍 Focus on early fraud peaks (Steps 25-49, 50-74, 100-124).

🔍 Monitor high-value transactions exceeding normal thresholds.

🔍 Target younger customer segments for proactive fraud prevention.

🔍 Implement real-time alerts for transactions with suspicious merchants & categories.

# 🏆 Conclusion

Fraudulent transactions in BankSim exhibit clear patterns, particularly:

✔ High fraud activity in early steps (0-74), peaking in 25-49 & 50-74.

✔ Younger age groups (0, 1, 2) are at higher risk.

✔ High-value transactions and specific merchants contribute significantly to fraud cases.

# 🔹 Next Steps:

🚀 Real-time fraud detection using Excel & SQL queries.

🚀 Integrating machine learning models to predict fraud in live transactions.

