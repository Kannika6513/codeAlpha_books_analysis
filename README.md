#📘 Book Data Scraping & Analysis Project
This repository contains my work for a data analysis internship project where I scraped, cleaned, and visualized book data from the website Books to Scrape. The project is divided into three major tasks:

#Task 1: Web Scraping – Extract Book Data
In this task, I built a Python-based web scraper using requests and BeautifulSoup to extract information from 50 pages of books listed on the BooksToScrape website. The data collected includes:

Title

Price (GBP)

Rating

Genre

The scraped data was saved in a structured format (CSV file) for further analysis.

🔄 I ensured all pages were iterated through and also scraped inner book pages to extract the genre field, making the dataset richer.

 Task 2: Exploratory Data Analysis (EDA)
The main objective of Task 2 was to explore and understand the dataset. Key steps included:

✅ Dataset loading and preview

✅ Data type check using df.info()

✅ Missing values check

✅ Summary statistics of Price (describe())

✅ Genre-wise average price calculation

✅ Frequency counts for Ratings and Genres

✅ Duplicate data check

✅ Outlier detection using boxplots

🧠 This task helped uncover data insights and check for data integrity before visualization.

📈 Task 3: Data Visualization
Here, I visualized key patterns in the dataset using Matplotlib and Seaborn. The visualizations include:

Top 10 Genres by book count

Book count by Genre and Rating (grouped bar chart)

Genre vs Average Price

Rating vs Average Price

Top 5 most expensive books

Comparison of genres with the highest average price

Distribution of book prices

Count of books per rating level

🎯 All visualizations are designed to extract business or user behavior insights and enhance data storytelling.
