## Data Pipeline and ETL Process with Power BI and PostgreSQL

### About the Dataset
- Amazon is one of the biggest online retailers in the UK. With this dataset, there is depth idea of what products sell best, which SEO titles generate the most sales, the best price range for a product in a given category, and much more.
- A massive dataset with 2.2 million Amazon products. Includes titles, num of reviews, ratings, prices, and sales data from October 2023
- URL to download this data: https://s3.amazonaws.com/fast-ai-nlp/amazon_review_full_csv.tgz

### ETL Process
- This project Utilized Python's Pandas library to extract, transform, and load the data into a PostgreSQL database.

### Visualization
- Power BI is used to visualize the meaningful insights by connecting to PostgreSQL database.
- #### Visualization list
    - Sum of boughtInLastMonth by categoryName
    - Sum of price and Sum of stars by categoryName
    - Sum of reviews and Sum of price by categoryName
    - Sum of stars, Sum of boughtInLastMonth and Sum of price by isBestSeller
    - Sum of stars by categoryName
    - Sum of stars and Sum of reviews by title


## About Us
| No. | Name               | ID              |
| --- | ------------------ | --------------- |
|  1  | Belay Birhanu      | DBUR/0571/12    |
|  2  | Hailemichael Adisu | DBUR/0210/12    |
|  3  | Betelehem Yitagesu | DBUR/1384/12    |
|  4  | Abraham Shiferaw   | DBUR/0704/12    |
|  5  | Dagmawit Tsegaye   | DBUR/1895/12    |
