# Big Data Processing with Apache Spark

<img src="https://github.com/gprzy/credit-scoring/blob/main/assets/puc.png" width="30%" height="30%"/> <br>

[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gprzy/transactions-pyspark/blob/main/transactions_pyspark_rdd.ipynb)
[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gprzy/transactions-pyspark/blob/main/transactions_pyspark_sql.ipynb)

This repository is a final project about Big Data topic on Computer Science college. In order to answer some questions and extract insights through the processing, summarization and grouping of an extensive dataset, `pyspark` was used, from which two equivalent solutions were presented: one using RDD (resilient distributed dataset, and the other using SQL.

# Project description

You and your team were hired to process data using Apache Spark. Your company has access to a dataset with commercial transactions between countries during the past 30 years. For each transaction,
the dataset contains the following variables:

| Variable (column)    |Description    |
| ---------------------|---------------| 
| `Country`              | Country involved in the commercial transaction | 
| `Year`                 | Year in which the transaction took place      |  
| `Commodity code`       | Commodity identifier      | 
| `Commodity`| Commodity description |
| `Flow` | Flow, e.g. Export or Import |
| `Price` | Price, in USD |
| `Weight` | Commodity weight |
| `Unit` | Unit in which the commodity is measured, e.g. Number of items |
| `Amount` | Commodity amount given in the aforementioned unit |
| `Category` | Commodity category, e.g. Live animals |

The dataset has over 8 million instances (rows, or commercial transactions). The dataset is made available in CSV format. Columns are separated by semi-colons (“ ; ”).

## Questions to be answered

Given the aforementioned context, you are in charge of developing a set of solutions that allow
the company to answer the following demands:
- [X] 1. The number of transactions involving Brazil;
- [X] 2. The number of transactions per year;
- [X] 3. The most commercialized commodity (summing the quantities) in 2016, per flow type;
- [X] 4. The average of commodity values per year;
- [X] 5. The average price of commodities per unit type, year, and category in the export flow in
Brazil;
- [X] 6. The commodity with the highest price per unit type and year;
- [X] 7. The number of transactions per flow type and year;

**BONUS ACTIVITY:**
- If you and your team properly answer the same questions given above using `SparkSQL` and reach
the same results obtained with traditional `RDD` and `PairRDD` programming.
