# Ecommerce Product Scraper

A Python web scraping project that extracts product information from the Books to Scrape demo website and stores it in a CSV file.

## Features

- Extracts Product Name
- Extracts Price
- Extracts Rating
- Saves data into CSV
- Easy to modify for other websites (where permitted)

## Technologies Used

- Python
- Requests
- BeautifulSoup
- CSV

## Installation

```bash
pip install requests beautifulsoup4
```

## Run

```bash
python product_scraper.py
```

## Output

Creates a file named:

```
products.csv
```

containing:

- Product Name
- Price
- Rating

## Project Structure

```
Ecommerce-Product-Scraper/
│
├── product_scraper.py
├── products.csv
├── README.md
└── requirements.txt
```

## Author

Rithik Kumar
