# 🏢 Automated Data Extraction — Largest Companies in the USA

## 📌 Overview
This project automates the extraction of tabular data from a website listing the largest companies in the USA. Using Python libraries **BeautifulSoup** and **Pandas**, the project scrapes company names, revenues, and other key details from an HTML table and exports the data into a structured CSV file for further analysis.

## 🛠 Tools & Libraries Used
- Python
- BeautifulSoup (for web scraping)
- Pandas (for data manipulation)
- Requests
- Jupyter Notebook

## 💡 What This Project Does
- Sends an HTTP request to the target webpage.
- Parses the HTML content using BeautifulSoup.
- Locates and extracts the table containing company data.
- Cleans and structures the extracted data using Pandas.
- Exports the final, organized data to a CSV file for analysis.

## 📁 Files Included
- `webscraping.ipynb` — Jupyter Notebook containing the complete data extraction and cleaning workflow.
- `companies.csv` — Cleaned dataset exported as a CSV file.
- `README.md` — Project documentation.

## 📊 Sample Data Fields
- Company Name
- Industry
- Revenue (USD)
- Number of Employees
- Headquarters Location

## 📈 Future Improvements
- Add error handling for failed web requests.
- Automate scheduled data extraction.
- Include additional metrics like market capitalization or global ranking.

---

