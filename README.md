# project-3-web-scraping-

This Python project demonstrates a web scraping script using the requests and BeautifulSoup libraries. The script extracts book information, including the title, price, and availability, from the website BooksToScrape and saves it as a CSV file using pandas.

Features
Scrapes the homepage of BooksToScrape.com.
Extracts details such as:
Book Title
Price
Availability
Saves the extracted data into a CSV file (books.csv) for further analysis.
Technologies Used
Python
Requests: for sending HTTP requests to fetch web content.
BeautifulSoup: for parsing and navigating the HTML content.
Pandas: for structuring and saving the data in CSV format.
How to Use
Clone this repository or copy the script.
Make sure you have Python installed.
Install the required libraries by running:
bash
Copy code
pip install requests beautifulsoup4 pandas
Run the script:
bash
Copy code
python script_name.py
The scraped data will be saved in a file named books.csv.
Notes
The script is designed to scrape data only from the homepage of BooksToScrape.com.
Ensure that you comply with the website's terms of service when scraping.
