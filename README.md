# Analyzing-Amazon-s-Best-Selling-Books-with-Pandas

## Project Overview
This project analyzes Amazon’s top 50 bestselling books from 2009 to 2019 using Python and the Pandas library. The goal is to explore sales trends, identify popular genres, examine pricing patterns, and gain insights into customer ratings over the years

## Dataset Description
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019?resource=download) and contains the following columns:

- Name – Title of the book
- Author – Name of the author
- User Rating – Average customer rating (out of 5)
- Reviews – Number of customer reviews
- Price – Price of the book in USD
- Year – Year the book appeared as a bestseller
- Genre – Fiction or Non-Fiction

This structured dataset allows for various analytical approaches, including exploratory data analysis (EDA), data visualization, and statistical insights into book sales trends.

## Project Structure
- Data Loading: Read the dataset using Pandas.
- Exploratory Data Analysis (EDA): Use various functions from the pandas library to explore the data and understand its structure, shape, and statistics. Visualized data using Matplotlib and Seaborn to understand the data further.
- Data Cleaning: Once the data is explored, it might need to be cleaned before running an analysis. To clean the data, drop duplicates, rename columns, and convert data types.
- Statistical Insights: Analyzed author popularity, calculated the average price of the books over the years, analyzed rating by Genres and finally compared genres in terms of ratings and reviews.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run the Project
1. Clone the repository.
2. Upload the .ipynb file and the bestsellers.csv to Google Colab.
3. Run the code cells.

## Results & Insights
- Author Popularity: Certain authors appear multiple times in the bestseller list, indicating a strong following and consistent success.
- Book Pricing Trends: The average price of bestselling books has remained relatively stable over the years, with some fluctuations. Fiction books tend to have a slightly lower average price compared to non-fiction books.
- Genre-Based Rating Analysis: Fiction books generally receive higher ratings on average compared to non-fiction books, though the latter has more variability in ratings.
- Comparison of Genres (Ratings & Reviews):
  1. Fiction books tend to accumulate more reviews, suggesting greater engagement from readers.
  2. Nonfiction books, despite having fewer reviews, often maintain strong ratings, indicating a niche but satisfied readership.
