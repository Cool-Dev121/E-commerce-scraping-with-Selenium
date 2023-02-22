SignorVino Wine E-commerce Webscraping

This project is a web scraping tool for the SignorVino wine e-commerce website. It uses the Python Selenium library to extract data from the website. The code is designed to run in less than 5 minutes on an average laptop.

Installation

To use this tool, you will need to have Python and the Selenium library installed. You can install Selenium using pip:

pip install selenium

You will also need to download and install the appropriate web driver for your browser. For example, if you are using Google Chrome, you will need to download the Chrome driver. You can find more information about how to do this in the Selenium documentation.

Usage

To use this tool, simply run the webscraper.py script. The output will be five Excel files containing data on the different types of wines available on the website:

red_wines.xlsx: Only red wines
white_wines.xlsx: Only white wines
sparkling_wines.xlsx: Only sparkling wines
sweet_wines.xlsx: Only sweet wines
all_wines.xlsx: All wines

# Example usage of the webscraper.py script
from webscraper import scrape_website

scrape_website()

Please note that this code is designed for educational purposes only. Scraping static pages such as the one used for this project can be done more easily with simpler libraries like Beautiful Soup.

Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome any contributions, whether it be bug fixes, new features, or improvements to the documentation.
