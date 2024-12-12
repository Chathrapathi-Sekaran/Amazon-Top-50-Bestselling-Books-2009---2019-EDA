# Amazon Top 50 Bestselling Books (2009 - 2019) - Exploratory Data Analysis

## Project Overview
This project involves an exploratory data analysis (EDA) of the Amazon Top 50 Bestselling Books dataset from 2009 to 2019. The objective is to analyze trends, extract insights, and identify patterns related to bestselling books, authors, user ratings, reviews, prices, and genres.

---

## Dataset Overview

### Dataset Summary
- **Total Rows:** 550
- **Total Columns:** 7
- **Null Values:** None
- **Key Observations:**
  - Books with Price Zero: 9 books
  - Maximum Book Price: $105
  - Unique Books: 351
  - Unique Authors: 248
  - Total Reviews: 6,574,305
  - Genres: Fiction and Non-fiction

### Data Dictionary
| Column Name   | Description                              | Datatype   |
|---------------|------------------------------------------|------------|
| Name          | Name of the bestselling book            | Object     |
| Author        | Author of the bestselling book          | Object     |
| User Rating   | User Rating of the book                 | Float      |
| Reviews       | Number of reviews for the book          | Integer    |
| Price         | Price of the book                       | Integer    |
| Year          | Year when it was a bestseller           | Integer    |
| Genre         | Categorized as Fiction or Non-fiction   | Object     |

---

## Analysis and Insights

### 1. Genre-Wise Split-up
- **Non-Fiction:** 310 books
- **Fiction:** 240 books

### 2. User Rating Analysis
- **Highest Rated Books:** 28 unique books with a rating of 4.9.
- **Mean User Rating:** 4.62
- **Median User Rating:** 4.7
- **Lowest Rated Book:**
  - *"The Casual Vacancy"* by J.K. Rowling (2012), rated 3.3.
- **Books with Consistently High Ratings:**
  - J.K. Rowling’s later 4 books in the Harry Potter series (rated 4.9).
  - Dav Pilkey’s "Dog Man" series includes 6 books with a 4.9 rating.

### 3. Reviews Analysis
- **Maximum Reviews:** *"Where the Crawdads Sing"* by Delia Owens.
- **Minimum Reviews:** *"Divine Soul Mind Body Healing and Transmission"* by Zhi Gang Sha.

### 4. Pricing Trends
- **Maximum Price:** $105
- **Books Priced at Zero:** 9
- **Average Price:** Dropped from $15 to around $10 between 2009 and 2019.

### 5. Observations on Trends
- **Mean User Rating:**
  - Trend shows an increase from 4.5 to 4.75 on average.
- **Total Number of Reviews:**
  - Plateaued at around 65K to 80K since 2012.
- **Average Price:**
  - Gradually dropped from $15 to $10 over the decade.

### 6. Genre-Specific Insights
- **Fiction:**
  - Higher user ratings and a higher number of reviews compared to Non-Fiction.
- **Non-Fiction:**
  - Lower average ratings and fewer reviews compared to Fiction.

---

## Key Findings

### Top-Selling Books and Authors
- **Top Authors:**
  - J.K. Rowling (Harry Potter series)
  - Dav Pilkey (Dog Man series)
  - Delia Owens (*"Where the Crawdads Sing"*)
- **Popular Books:**
  - Harry Potter series
  - Dog Man series
  - *"Where the Crawdads Sing"*

### Pricing and User Ratings
- Books with higher user ratings tend to have a larger number of reviews.
- The price of books has become more affordable over time, possibly driving higher user engagement.

---

## Conclusion
The EDA of the Amazon Top 50 Bestselling Books dataset provides valuable insights into trends in book sales, genres, pricing, and popularity. This analysis highlights how user preferences and market trends evolved between 2009 and 2019, offering actionable insights for publishers, authors, and readers.

---

## Tools and Technologies Used
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

---

## Repository Structure
- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks with code for analysis.
- `README.md`: Project documentation.

---

## How to Use
1. Clone the repository.
2. Open the Jupyter notebook in the `notebooks` folder.
3. Follow the code to replicate the analysis and explore additional insights.


