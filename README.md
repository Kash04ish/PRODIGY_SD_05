Product Information Scraper
This project is a Python-based web scraping tool that extracts product information (names, prices, and ratings) from an e-commerce website and stores the data in a CSV file.

Table of Contents
Overview
Features
Installation
Usage
Dependencies

Overview
This script scrapes product data from a demo e-commerce website, http://books.toscrape.com/. The extracted data includes product names, prices, and ratings. The data is then stored in a CSV file for easy access and analysis.

Features
Scrapes product names, prices, and ratings from the website.
Stores extracted data in a structured CSV file.
Easy to use and modify for other websites (with minor adjustments).
Installation
Clone the repository:
git clone https://github.com/Kash04ish/PRODIGY_SD_05.git
Change into the project directory:
cd PRODIGY_SD_05
Usage
Ensure you have Python installed on your system (preferably Python 3.6+).
Run the script:
python PRODIGY_SD_05.py
The script will create a file named amazon_data.csv in the same directory, containing the scraped product data.

Dependencies
requests: To send HTTP requests to the website.
beautifulsoup4: To parse HTML content and extract data.
csv: To write the extracted data to a CSV file.
