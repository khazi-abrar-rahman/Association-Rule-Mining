# Association-Rule-Mining
This project demonstrates Association Rule Mining using the Apriori algorithm to uncover meaningful relationships between products in transactional data. The analysis is performed on the Online Retail dataset and focuses on identifying frequently purchased itemsets and generating strong association rules based on support, confidence, and lift metrics.

# Project Overview
Loads and preprocesses retail transaction data from an Excel file
Converts transaction quantities into a binary (0/1) basket format
Applies the Apriori algorithm to extract frequent itemsets
Generates association rules using lift as the primary evaluation metric
Filters strong rules with high confidence and lift values

# Technologies Used
Python
Pandas & NumPy
mlxtend.frequent_patterns (Apriori & Association Rules)

# Key Features
Efficient market basket analysis
Custom encoding of transactional data
Identification of high-value product associations
Rule filtering for actionable insights

