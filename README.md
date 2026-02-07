# CodeAlphaTask-1
Data Visualization(Web Scrapping)
INSIGHTS:

1. Successful Data Extraction
The web scraping process successfully extracted structured book data including title, price, and rating from a public website. This demonstrates the effectiveness of using Python libraries such as requests and BeautifulSoup for real-world data collection.

2. Price Distribution Pattern
Analysis of book prices shows that most books are priced within a moderate range, with only a few books having significantly higher prices. This indicates a pricing strategy focused on affordability for a wider audience.

3. Rating Distribution Trend
The majority of books fall into mid-range ratings (3 and 4 stars), suggesting generally positive but not extreme user feedback. Very low and very high ratings occur less frequently.

4. Price vs Rating Relationship
Visualization reveals no strong correlation between book price and rating. Higher-priced books do not necessarily receive higher ratings, indicating that price is not the sole indicator of perceived quality.

5. Presence of Outliers
Box plot analysis identified a small number of books with exceptionally high prices, highlighting outliers that may represent special editions or niche publications.

6. Data Quality Improvement
The raw scraped data contained encoding issues in price values (currency symbols). These were successfully cleaned, converting all values into numeric format suitable for analysis.

CONCLUSION:

1. Effectiveness of Web Scraping
Web scraping proved to be an efficient method for collecting real-time data from publicly available web pages, enabling the creation of a custom dataset without relying on pre-existing sources.

2. Importance of Data Cleaning
The project highlighted that scraped data often contains inconsistencies such as encoding errors and textual values. Proper data cleaning is essential before performing any analysis.

3. Value of Visualization
Visualizations such as bar charts, histograms, scatter plots, box plots, and pie charts made it easier to identify trends, distributions, and anomalies in the dataset.

4 Analytical Insight Generation
Even with a small dataset, meaningful insights regarding pricing patterns and customer ratings can be derived, supporting data-driven decision-making.

5. Scalability for Future Work
The implemented scraping and cleaning approach can be extended to multiple pages or similar websites to build larger datasets for advanced analysis and predictive modeling.
