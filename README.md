Amazon Top 50 Bestselling Books (2009 - 2019) Analysis
This project analyzes the Amazon Top 50 Bestselling Books from 2009 to 2019 to explore trends in popularity, 
rating differences between genres, and changes in average ratings over the last three years.

Dataset Overview
The dataset includes:

Name: Book title
Author: Author's name
User Rating: Average rating (1 to 5)
Reviews: Number of user reviews
Price: Price in USD
Year: Year of publication
Genre: Fiction or Non-Fiction

Objectives
Which books became popular more often?
How does the rating differ between fiction and non-fiction?
Are average book ratings different for the last three years (2017-2019)?

Key Findings

1. Book Popularity by Genre
Test: Binomial Test
Result: p-value = 0.00322
Conclusion: Fiction and non-fiction books have significantly different popularity levels.

2. Rating Differences Between Genres
Test: T-test (after checking normality and equal variances)
Result: p-value = 0.00287
Conclusion: Average ratings for fiction and non-fiction are significantly different.

3. Rating Trends (2017-2019)
Test: ANOVA
Result: p-value = 0.053
Conclusion: No significant change in average ratings over these years.

Technologies Used
Python (Pandas, NumPy, SciPy) for data analysis and statistical tests.
