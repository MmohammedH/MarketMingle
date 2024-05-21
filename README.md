# MarketMingle

# Market Basket Analysis Using Apriori Algorithm
This project performs Market Basket Analysis using the Apriori algorithm to find associations between products in transaction data. The analysis helps in understanding customer purchase behaviors, which can be utilized to optimize product placement and promotional strategies.

# Introduction
Market Basket Analysis is a data mining technique used to identify associations between products purchased together. This project uses the Apriori algorithm to discover frequent itemsets and generate association rules from transaction data.

# Dataset
The dataset consists of 7,501 transactions, each containing between 1 and 20 items. The data is provided in a CSV file with each row representing a transaction and columns representing items.
# Link:https://www.kaggle.com/datasets/sivaram1987/association-rule-learningapriori

# Methodology
# Data Preprocessing
Load the transaction data from the CSV file.
Transform the data into a dataframe format suitable for the Apriori algorithm.
# Applying the Apriori Algorithm
Use the Apriori algorithm to identify frequent itemsets.
Generate association rules from the frequent itemsets with specified minimum confidence and lift thresholds.
