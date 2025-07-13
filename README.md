# Lebanese Lottery Result Scraper
This project scrapes the official Lebanese lottery website to collect and organize draw results. It allows users to fetch past draw data (draw numbers, dates, and winning numbers) in a structured format suitable for analysis or storage.

# Objective
To automate the extraction of Lebanese lottery results from the official site and convert them into a clean, structured dataset for analysis or tracking.

# Data Source
Official site: https://www.lldj.com

Draws are accessed by draw number via URLs like:

https://www.lldj.com/en/LatestResults?draw=<draw_number>

# Features
Fetches latest or specific draw results using the draw number

Parses HTML content using BeautifulSoup

Stores results in a pandas DataFrame

Outputs clean tabular data for further use (CSV, display, etc.)

# Libraries Used
requests – to send HTTP GET requests

# How to Use

Clone the repo:

BeautifulSoup – to parse HTML and extract lottery data

pandas – to organize and store draw results

Open the notebook:

jupyter notebook loto.ipynb

Run the cells to:

Scrape results for a draw number (e.g., scrape_draw_results(2000))

View or export the data

Contact

📧 mohanadmfarhat80@gmail.com
