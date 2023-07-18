# GitHub README - Web Scraping Job Listings of Successfactors

This repository contains a Python script that demonstrates web scraping job listings from a specific website. The script utilizes the `playwright` library to automate web browsing, and `BeautifulSoup` for HTML parsing. It also uses the `pandas` and `requests` libraries for data manipulation and HTTP requests, respectively.

## Requirements

- Python 3.7 or higher
- Playwright library: `pip install playwright`
- BeautifulSoup library: `pip install beautifulsoup4`
- Pandas library: `pip install pandas`
- Requests library: `pip install requests`

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/your-repository.git
```

2. Install the required libraries:

```
pip install playwright beautifulsoup4 pandas requests
```

3. Run the script:

```
python scrape_job_listings.py
```

The script will scrape job listings from the target website and save them in a CSV file named `Um6p_Jobs.csv`.

## Project Structure

- `scrape_job_listings.py`: The main Python script that performs web scraping and data processing.
- `full_html_job.html`: The HTML file containing the scraped job listings.
- `img*.png`: Screenshots of each page during the scraping process (optional).

## Disclaimer

Please note that web scraping should be done responsibly and in compliance with the website's terms of service. This script is provided as an example for educational purposes only. Use it responsibly and respect the website's policies and limitations.

If you have any questions or encounter any issues, please feel free to open an issue in this repository.

Happy scraping!
