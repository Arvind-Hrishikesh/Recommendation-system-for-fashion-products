# Recommendation-system-for-fashion-products
Applied machine learning group project on H&amp;M dataset

## Part 1
Finished.

## Part 2

Deadline: 11/07/2022

Submit a presentation with 8-10 slides with notes covering:

1. Initial data exploration
2. Cleaning and sampling
3. Insights from data exploration and
4. Machine Learning techniques proposed to be implemented


## Data
https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data

## Work Distribution
Zhe and Pooja: articles.csv

Arvind and Tom: transactions.csv, images

Ayushi: customers.csv, images

## Notes

### Tom:

Transactions.csv summary:

- Rows: each row represents a transaction of the purchases in H&M group.
- Columns:
  - t_dat: date of the transaction
  - customer_id: a foreign key that maps to each customer entry in the customer_id column in customers.csv, which contains customers' metadata
  - article_id: a foreign key that maps to each customer entry in the article_id column in articles.csv, which contains articles' metadata
  - price: price that the customer paid for the transaction, there are multiple prices for the same article, even on the same day/channel. According to data's contributor, the unit of price is not any "currency/unit" since they chose to not disclose the real values
  - sales_channel_id: it determines how the customer purchases the article, 2 is online and 1 store

## Useful information
