# 📘 Book Data Scraping & Analysis Project

This repository contains my work for a **data analysis internship project** where I scraped, cleaned, and visualized book data from the website [Books to Scrape](https://books.toscrape.com/). The project is divided into three major tasks:

---

## 🧪 Task 1: Web Scraping – Extract Book Data

In this task, I built a **Python-based web scraper** using `requests` and `BeautifulSoup` to extract information from **50 pages of books** listed on the BooksToScrape website.

📦 **Data fields collected:**
- Title
- Price (GBP)
- Rating
- Genre

✅ I scraped not only the listing pages but also the **inner book pages** to extract the **Genre**, enriching the dataset with more valuable information.

🗂️ The final data was saved as a structured **CSV file** for further analysis.

---

## 📊 Task 2: Exploratory Data Analysis (EDA)

The objective of Task 2 was to perform **basic exploratory analysis** on the scraped dataset using **Pandas** and **Matplotlib**.

🔍 **Key EDA steps:**
- Dataset loading and preview
- Data type inspection using `df.info()`
- Missing values check
- Summary statistics (`describe()`)
- Genre-wise average price calculation
- Frequency counts for Ratings and Genres
- Duplicate data check
- Outlier detection using boxplots

🧠 This step helped uncover hidden insights and ensured data quality before moving to visualizations.

---

## 📈 Task 3: Data Visualization

This task focuses on **visualizing patterns and trends** in the dataset using `Seaborn` and `Matplotlib`.

📉 **Visualizations created:**
- 📚 Top 10 Genres by Book Count
- 📊 Book Count by Genre and Rating (Grouped Bar Chart)
- 💸 Genre vs Average Price
- ⭐ Rating vs Average Price
- 💰 Top 5 Most Expensive Books
- 🧾 Genres with the Highest Average Price
- 📈 Distribution of Book Prices
- ⭐ Count of Books per Rating Level

🎯 These visualizations reveal important insights into customer preferences, pricing strategies, and genre popularity.

---

## 🛠️ Tools & Libraries Used

- Python  
- Jupyter Notebook
- Pandas  
- Matplotlib  
- Seaborn  
- BeautifulSoup  
- Requests  

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `task1.py` | Python script for scraping the book dataset |
| `scraped_bookdata.csv` | Cleaned dataset |
| `task2.ipynb` | Exploratory Data Analysis notebook |
| `task3.ipynb` | Data Visualization notebook |
| `README.md` | Project overview and documentation |

---

## 🙏 Acknowledgements

Special thanks to **[BooksToScrape](https://books.toscrape.com/)** for providing an excellent dataset for practice in web scraping and data analysis.

---

