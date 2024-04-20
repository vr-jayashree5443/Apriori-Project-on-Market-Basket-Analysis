# Apriori-Project-on-Market-Basket-Analysis

This project involves implementing the Apriori algorithm to analyze transaction data and extract frequent itemsets.

### Introduction

The Apriori algorithm is a popular algorithm used in data mining for association rule learning. It is particularly useful for finding frequent itemsets in transactional databases.

- **Libraries Used**:
  - `numpy`: For numerical computing.
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` and `seaborn`: For data visualization.
  - `apyori`: For implementing the Apriori algorithm.
- **Dataset**:
  - The dataset used in this project is sourced from the following URL: [Groceries_dataset.csv](https://raw.githubusercontent.com/amankharwal/Website-data/master/Groceries_dataset.csv)

### Steps 

1. **Importing Libraries**: Necessary libraries are imported including `numpy`, `pandas`, `matplotlib`, `seaborn`, and `apyori`.

2. **Installing the Apriori Package**: The `apyori` package is installed to enable the implementation of the Apriori algorithm.

3. **Importing the Dataset**: The dataset containing transaction data is imported from the provided URL.

4. **Data Exploration**:
   - Information about the dataset such as its shape, size, and missing values is explored.
   - Analysis is performed to find top selling items, least selling items, and the top 10 selling items.
   - Analysis is also conducted to find the top 10 customers.

5. **Transaction Analysis**:
   - The majority of transactions happened in which year and month is analyzed.
   - Specific analysis is performed for the year 2015 to find the month with the majority of transactions, as well as the specific day within that month.

6. **Apriori Implementation**:
   - The dataset is prepared for Apriori implementation by encoding item descriptions into binary format.
   - Apriori algorithm is applied to find frequent itemsets in the transaction data.

### Conclusion

This project demonstrates the implementation of the Apriori algorithm for analyzing transaction data to identify frequent itemsets. It covers various steps including data exploration, transaction analysis, and Apriori implementation to derive meaningful insights from the dataset.
