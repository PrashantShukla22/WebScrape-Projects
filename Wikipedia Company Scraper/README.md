# Wikipedia Web Scraping Project: Largest Companies in the United States by Revenue

## Project Overview
This project involves web scraping data from the Wikipedia page: [List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue). The script extracts structured information about the companies, including:
- Company name
- Industry
- Revenue (in billion USD)
- Number of employees
- Headquarters location

The scraped data is saved in a CSV file for further analysis.

---

## Files in the Repository
1. **`wikipedia_scraper.py`**  
   The Python script used for scraping data. It leverages the following libraries:
   - `requests` for sending HTTP requests
   - `BeautifulSoup` from `bs4` for parsing HTML content
   - `pandas` for data manipulation and saving results to CSV

2. **`us_companies_by_revenue.csv`**  
   The resulting CSV file containing the scraped data in a tabular format.

3. **`README.md`**  
   Documentation for the project, including setup instructions, project details, and usage examples.

---

