# Google-map-scraper
 Python 3.x

 Selenium

BeautifulSoup (bs4)

 Google Chrome

ChromeDriver

# Installation

Clone the repository:

git clone https://github.com/yourusername/google-map-scraper.git

Navigate to the project directory:

cd google-map-scraper

Install the required Python packages:

pip install -r requirements.txt

# Setup

Download the appropriate version of ChromeDriver from here and place it in the project directory.

Make sure Google Chrome is installed and updated to the version compatible with ChromeDriver.

# Usage

Update the config.py file with your target search terms and any other configurations such as the number of pages to scrape.

Run the scraper:

python scraper.py

The scraped data will be saved in the output directory in CSV format.

# Configuration

The config.py file contains settings that control the behavior of the scraper. You can update the following parameters:

SEARCH_TERM: The term to search for on Google Maps.

NUM_PAGES: The number of pages to scrape.

OUTPUT_FILE: The name of the output CSV file.

# Example

To scrape information about "coffee shops in New York":

Set SEARCH_TERM in config.py to "coffee shops in New York".

Run the scraper using:

python scraper.py

Check the output directory for the CSV file containing the scraped data.

Contributing

Fork the repository.

Create a new branch:

git checkout -b feature-branch-name

Commit your changes:

git commit -m 'Add some feature'

Push to the branch:

git push origin feature-branch-name

Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for more information.


